# Examples

## Linters

=== "Shell"
    --8<-- "lint/shell/all.md"

=== "YAML"
    --8<-- "lint/yaml/all.md"

=== "Dockerfile"
    --8<-- "lint/docker/all.md"

=== "Ansible"
    --8<-- "lint/ansible/all.md"

=== "Markdown"
    --8<-- "lint/markdown/all.md"

## Notification

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/notifications/pushover.yml’
```

## Analysis

=== "SAST"
    --8<-- "analysis/sast.md"


## Ansible Playbook

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/ansible/runner.yml’
```

## Postman API Test

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/api/postman.yml’
```
