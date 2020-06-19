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

## Syntax Linters

=== "Shell"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/shell/all.yml’
    ```

=== "YAML"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/yamllint.yml’
    ```

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
