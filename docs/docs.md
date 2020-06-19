# Documentation Generation

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

### Extension Reference

* [admonition](https://squidfunk.github.io/mkdocs-material/extensions/admonition/)
* [codehilite](https://squidfunk.github.io/mkdocs-material/extensions/codehilite/)
* 

### Plugins Reference

[Master Plugin List](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Plugins)

* [https://github.com/athackst/mkdocs-simple-plugin](https://github.com/athackst/mkdocs-simple-plugin)
* [http://www.lyonthackston.com/mkdocs-simple-plugin](http://www.lyonthackston.com/mkdocs-simple-plugin/)
* [https://github.com/midnightprioriem/mkdocs-toc-sidebar-plugin](https://github.com/midnightprioriem/mkdocs-toc-sidebar-plugin)
* [https://mkdocs-macros-plugin.readthedocs.io/en/latest](https://mkdocs-macros-plugin.readthedocs.io/en/latest)
* [https://github.com/fralau/mkdocs_macros_plugin](https://github.com/fralau/mkdocs_macros_plugin)
* [https://github.com/rosscdh/mkdocs-markdownextradata-plugin](https://github.com/rosscdh/mkdocs-markdownextradata-plugin)
