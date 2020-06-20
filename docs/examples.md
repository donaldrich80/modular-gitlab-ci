# Examples


## Linters

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

=== "Dockerfile"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/docker/all.yml’
    ```

=== "Ansible"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/ansible.yml’
    ```

=== "Markdown"
    ``` yaml
    include:
      - project: ‘donaldrich/gitlab-ci-templates’
        file: ‘/lint/markdown.yml’
    ```

=== "Markdown2"
    --8<-- "test.md"

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
