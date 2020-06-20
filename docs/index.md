# Modular GitLab-CI

!!! note
    This documentation serves a double function. To document this repo, as well as to serve as internal reference for me as an aggregate for external reference links to the tools used by it.

!!! warning
    This is a living document, and sometimes life is messy.

--8<-- "test.md"

## About

Modular templates for use in GitLab-CI pipelines.

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml

Example:

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/lint/shellcheck.yml’
```

## Todo

- [ ] vault integration
- [ ] extensions
  - [ ] ssh
  - [ ] terraform
  - [ ] packer
  - [ ] ansible

## Test

```mermaid
graph TB
    c1–>a2
    subgraph one
    a1–>a2
    end
    subgraph two
    b1–>b2
    end
    subgraph three
    c1–>c2
    end
```

[=85% “85%”]{: .candystripe}
[=100% “100%”]{: .candystripe .candystripe-animate}

[=0%]{: .thin}
[=5%]{: .thin}
[=25%]{: .thin}
[=45%]{: .thin}
[=65%]{: .thin}
[=85%]{: .thin}
[=100%]{: .thin}
