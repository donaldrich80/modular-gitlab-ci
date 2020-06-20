# Modular GitLab-CI

Modular templates for use in GitLab-CI pipelines.

## How it works

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml. 

This library includes a wide range of functionality, and will be expanded over time.

## Example

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

!!! note
    This documentation serves a double function. To document this repo, as well as to serve as internal reference for me as an aggregate for external reference links to the tools used by it.

!!! warning
    This is a living document, and sometimes life is messy.
