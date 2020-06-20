# Pushover

!!! note
    This function uses [Hashicorp Vault](https://www.vaultproject.io/) to import Pushover credentials.  If you aren't using Vault integration, you must declare them.

Neccesary Variables:

``` yaml
variables:
  PUSHOVER_ID: "Message shown in content"
```

Variables provided by Vault

``` yaml
variables:
  PUSHOVER_API_TOKEN:
  PUSHOVER_USER_TOKEN:
```

## Sounds

``` yaml
pushover - Pushover (default)
bike - Bike
bugle - Bugle
cashregister - Cash Register
classical - Classical
cosmic - Cosmic
falling - Falling
gamelan - Gamelan
incoming - Incoming
intermission - Intermission
magic - Magic
mechanical - Mechanical
pianobar - Piano Bar
siren - Siren
spacealarm - Space Alarm
tugboat - Tug Boat
alien - Alien Alarm (long)
climb - Climb (long)
persistent - Persistent (long)
echo - Pushover Echo (long)
updown - Up Down (long)
vibrate - Vibrate Only
none - None (silent)
```
