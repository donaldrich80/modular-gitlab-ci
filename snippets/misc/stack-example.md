``` yaml
include:
  - project: donaldrich/gitlab-ci-templates
    file: function/lint/yaml.yml
  - project: donaldrich/gitlab-ci-templates
    file: analysis/sast.yml
```