# Modular GitLab-CI

!!! note
    This documentation serves a double function. To document this repo, as well as to serve as internal reference for me as an aggregate for external reference links to the tools used by it.

!!! warning
    This is a living document, and sometimes life is messy.

## About

Modular templates for use in GitLab-CI pipelines.

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml

Example:

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/lint/shellcheck.yml’
```

Variables neccesary for Vault:

``` yaml
VAULT_ADDR:
VAULT_TOKEN:
```
