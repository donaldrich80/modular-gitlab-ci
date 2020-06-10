# GitLab-CI Templates

Modular templates for use in GitLab-CI pipelines.

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml

## Examples

### Pushover Notification
```
include:
  - project: 'donaldrich/gitlab-ci-templates'
    file:    '/notifications/pushover.yml'
```
### SAST Analysis
```
include:
  - project: 'donaldrich/gitlab-ci-templates'
    file:    '/analysis/sast.yml'
```
### Shellcheck
```
include:
  - project: 'donaldrich/gitlab-ci-templates'
    file:    '/lint/shellcheck.yml'
```
### Ansible Playbook
```
include:
  - project: 'donaldrich/gitlab-ci-templates'
    file:    '/ansible/runner.yml'
```
### Postman
```
include:
  - project: 'donaldrich/gitlab-ci-templates'
    file:    '/ansible/runner.yml'
```

## Reference
[https://github.com/Artemmkin/infrastructure-as-code-tutorial]

[https://docs.gitlab.com/ee/ci/variables/predefined_variables.html]

[https://github.com/ekino/docker-buildbox]

[https://github.com/nbedos/cistern]

[https://github.com/nemonik/hands-on-DevOps]

[https://github.com/sobolevn/dump-env]

[https://github.com/releaseworks/masterclass-codeexamples]

[https://github.com/firecow/gitlab-ci-local]

[https://github.com/BuBuaBu/gitlab-ci-lint]

[https://github.com/Grayda/gitlab-doc-builder]

[https://github.com/bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises)

https://github.com/analysis-tools-dev/static-analysis

https://github.com/analysis-tools-dev/dynamic-analysis/blob/master/README.md




