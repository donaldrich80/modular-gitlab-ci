# Examples


## Linters

=== "Shell"
    --8<-- "lint/shell-all.md"

=== "YAML"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/yamllint.yml’
    ```

=== "Dockerfile"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/docker/all.yml’
    ```

=== "Ansible"
    --8<-- "lint/ansible.md"

=== "Markdown"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/markdown.yml’
    ```

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
