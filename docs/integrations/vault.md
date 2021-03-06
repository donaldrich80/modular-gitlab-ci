---
title: Hashicorp Vault
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
---

# Hashicorp Vault

Security is a top consideration for this project (especially with public runners), which is why secret management is performed by Hashicorp Vault. However, a few secrets must be input into Gitlab to allow communication with your vault server.

JWT authentication is used, with bound issuer limited to the gitlab host, more information here.

!!! warning "Vault guide"

Variables neccesary for Vault:

```yaml
VAULT_ADDR:
VAULT_TOKEN:
```

https://docs.gitlab.com/ee/integration/vault.html
