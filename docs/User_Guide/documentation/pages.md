---
title: Pages
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
path: tree/master
source: function/documentation/mkdocs.yml
---

# GitLab Pages Generator

## Usage

To automatically generate GitLab Pages Docs, create a `mkdocs.yml` at the root of the project and add the following to the `.gitlab-ci.yml`

Include the following in `.gitlab-ci.yml`:
--8<-- "docs/mkdocs.md"

## Requirements

* `mkdocs.yml` file

* `documentation` stage:

```yaml
stages:
  - documentation
```

## Advanced

Detailed reference here.

### Use Gitlab-CI variables in mkdocs

GitLab-CI env variables can be passed to `mkdocs.yml` like so:

``` yaml
repo_name: !!python/object/apply:os.getenv ["CI_PROJECT_PATH"]
```
