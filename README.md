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

## DevOps & GitLab-CI References/Links
- [Artemmkin/infrastructure-as-code-tutorial](https://github.com/Artemmkin/infrastructure-as-code-tutorial)
- [https://docs.gitlab.com/ee/ci/variables/predefined_variables.html](https://docs.gitlab.com/ee/ci/variables/predefined_variables.html)
- [ekino/docker-buildbox](https://github.com/ekino/docker-buildbox)
- [nbedos/cistern](https://github.com/nbedos/cistern)
- [nemonik/hands-on-DevOps](https://github.com/nemonik/hands-on-DevOps)
- [sobolevn/dump-env](https://github.com/sobolevn/dump-env)
- [releaseworks/masterclass-codeexamples](https://github.com/releaseworks/masterclass-codeexamples)
- [firecow/gitlab-ci-local](https://github.com/firecow/gitlab-ci-local)
- [BuBuaBu/gitlab-ci-lint](https://github.com/BuBuaBu/gitlab-ci-lint)
- [Grayda/gitlab-doc-builder](https://github.com/Grayda/gitlab-doc-builder)
- [bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises)
- [analysis-tools-dev/static-analysis](https://github.com/analysis-tools-dev/static-analysis)
- [analysis-tools-dev/dynamic-analysis](https://github.com/analysis-tools-dev/dynamic-analysis)




