# Pushover

Receive pushover notification for pipeline or job events.

## Variables

!!! note
    This function uses [Hashicorp Vault](https://www.vaultproject.io/) to import Pushover credentials.  If you aren't using Vault integration, you must declare them.

Need to declare:

--8<-- "vars/pushover.md"

Provided by Vault

--8<-- "vars/vault/pushover.md"

## Sounds

--8<-- "notifications/pushover.md"
