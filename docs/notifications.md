# Notifications

## Pushover

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
