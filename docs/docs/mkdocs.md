path: tree/master
source: documentation/mkdocs.yml

# Documentation Generation

To automatically generate GitLab Pages Docs, create a 'mkdocs.yml' at the root of the project and add the following to '.gitlab-ci.yml'

``` yaml
include:
  - project: donaldrich/gitlab-ci-templates
    file: /documentation/mkdocs.yml
```

GitLab-CI env variables can be passed to mkdocs.yml like so:

``` yaml
repo_name: !!python/object/apply:os.getenv ["CI_PROJECT_PATH"]
```

## mkdocs

[mkdocs](https://www.mkdocs.org)

### Theme

[mkdocs-material](https://squidfunk.github.io/mkdocs-material/)

#### Design

* [colors](https://www.materialui.co/colors)

* [fonts](https://fonts.google.com/)

* [materialdesignicons](https://cdn.materialdesignicons.com/5.3.45/)

### Plugins Reference

[Master Plugin List](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Plugins)

#### [mkdocs-simple-plugin](https://github.com/athackst/mkdocs-simple-plugin) | [docs](http://www.lyonthackston.com/mkdocs-simple-plugin/)

Install:

``` sh
pip install mkdocs-simple-plugin
```

#### [https://github.com/rosscdh/mkdocs-markdownextradata-plugin](https://github.com/rosscdh/mkdocs-markdownextradata-plugin)

#### [https://github.com/midnightprioriem/mkdocs-toc-sidebar-plugin](https://github.com/midnightprioriem/mkdocs-toc-sidebar-plugin)

#### [mkdocs_macros_plugin](https://github.com/fralau/mkdocs_macros_plugin) | [docs](https://mkdocs-macros-plugin.readthedocs.io/en/latest)

### Misc

<https://stackoverflow.com/questions/49978926/concatenate-multiple-markdown-files-using-pandoc-on-windows>
