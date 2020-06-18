# Modular GitLab-CI

Modular templates for use in GitLab-CI pipelines.

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/ansible/runner.yml’
```
