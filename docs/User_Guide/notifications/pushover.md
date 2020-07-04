---
title: Notification
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
path: tree/master
source: function/lint/terraform
---

# Pushover

Receive pushover notification for pipeline or job events.

## Variables

!!! note
    This function uses [Hashicorp Vault](https://www.vaultproject.io/) to import Pushover credentials.  If you aren't using Vault integration, you must declare them.

Need to declare:

--8<-- "notifications/pushover/vars.md"

Provided by Vault

--8<-- "notifications/pushover/vault_vars.md"

## Sounds

--8<-- "notifications/pushover/sounds.md"
