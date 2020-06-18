# Examples

## Pushover Notification

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/notifications/pushover.yml’
```

## SAST Analysis

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/analysis/sast.yml’
```

## Shellcheck

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/lint/shellcheck.yml’
```

## Syntax Linters

``` yaml
include:
  - project: ‘donaldrich/gitlab-ci-templates’
    file: ‘/lint/default.yml’
```

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
