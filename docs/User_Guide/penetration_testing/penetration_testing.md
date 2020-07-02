# Penetration Testing

!!! danger
    This is integrated as a method of performing penetration tests on internal networks and to assess external vulnerabilities on my personal public facing assets!  Any other use is not condoned or endorsed!

## Sniper

``` yaml
include:
  - project: 'donaldrich/modular-gitlab-ci'
  - file: '/pentest/sniper.yml'

variables:
  PENTEST_TARGET: 192.168.1.1/16
  PENTEST_MODE: "stealth -o -re"
  PENTEST_REPORT: pentest-report
```

Basic Usage:

``` sh
sniper -c /path/to/sniper.conf -t <TARGET> -m <MODE> -w <WORKSPACE>
```

All Options:

``` sh
[*] NORMAL MODE
sniper -t <TARGET>
[*] SPECIFY CUSTOM CONFIG FILE
sniper -c /full/path/to/sniper.conf -t <TARGET> -m <MODE> -w <WORKSPACE>
[*] NORMAL MODE + OSINT + RECON
sniper -t <TARGET> -o -re
[*] STEALTH MODE + OSINT + RECON
sniper -t <TARGET> -m stealth -o -re
[*] DISCOVER MODE
sniper -t <CIDR> -m discover -w <WORSPACE_ALIAS>
[*] SCAN ONLY SPECIFIC PORT
sniper -t <TARGET> -m port -p <portnum>
[*] FULLPORTONLY SCAN MODE
sniper -t <TARGET> -fp
[*] WEB MODE - PORT 80 + 443 ONLY!
sniper -t <TARGET> -m web
[*] HTTP WEB PORT MODE
sniper -t <TARGET> -m webporthttp -p <port>
[*] HTTPS WEB PORT MODE
sniper -t <TARGET> -m webporthttps -p <port>
[*] HTTP WEBSCAN MODE
sniper -t <TARGET> -m webscan
[*] ENABLE BRUTEFORCE
sniper -t <TARGET> -b
[*] AIRSTRIKE MODE
sniper -f targets.txt -m airstrike
[*] NUKE MODE WITH TARGET LIST, BRUTEFORCE ENABLED, FULLPORTSCAN ENABLED, OSINT ENABLED, RECON ENABLED, WORKSPACE & LOOT ENABLED
sniper -f targets.txt -m nuke -w <WORKSPACE_ALIAS>
[*] MASS PORT SCAN MODE
sniper -f targets.txt -m massportscan -w <WORKSPACE_ALIAS>
[*] MASS WEB SCAN MODE
sniper -f targets.txt -m massweb -w <WORKSPACE_ALIAS>
[*] MASS WEBSCAN SCAN MODE
sniper -f targets.txt -m masswebscan -w <WORKSPACE_ALIAS>
[*] MASS VULN SCAN MODE
sniper -f targets.txt -m massvulnscan -w <WORKSPACE_ALIAS>
[*] PORT SCAN MODE
sniper -t <TARGET> -m port -p <PORT_NUM>
[*] LIST WORKSPACES
sniper --list
[*] DELETE WORKSPACE
sniper -w <WORKSPACE_ALIAS> -d
[*] DELETE HOST FROM WORKSPACE
sniper -w <WORKSPACE_ALIAS> -t <TARGET> -dh
[*] GET SNIPER SCAN STATUS
sniper --status
[*] LOOT REIMPORT FUNCTION
sniper -w <WORKSPACE_ALIAS> --reimport
[*] LOOT REIMPORTALL FUNCTION
sniper -w <WORKSPACE_ALIAS> --reimportall
[*] LOOT REIMPORT FUNCTION
sniper -w <WORKSPACE_ALIAS> --reload
[*] LOOT EXPORT FUNCTION
sniper -w <WORKSPACE_ALIAS> --export
[*] SCHEDULED SCANS
sniper -w <WORKSPACE_ALIAS> -s daily|weekly|monthly
[*] USE A CUSTOM CONFIG
sniper -c /path/to/sniper.conf -t <TARGET> -w <WORKSPACE_ALIAS>
[*] UPDATE SNIPER
sniper -u|--update
```
