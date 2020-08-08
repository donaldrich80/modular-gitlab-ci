``` yaml
include:
  - project: donaldrich/modular-gitlab-ci
    file: function/lint/yaml.yml
  - project: donaldrich/modular-gitlab-ci
    file: function/analysis/sast.yml
```