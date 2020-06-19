# Modular GitLab-CI

Modular templates for use in GitLab-CI pipelines.

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml

Example:

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/lint/shellcheck.yml’
```

!!! note
    This documentation serves a double function. To document this repo, as well as to serve as internal reference for me as an aggregate for external reference links to the tools used by it. It is a living document, and life is messy sometimes.
