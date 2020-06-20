path: tree/master
source: documentation/mkdocs.yml

# GitLab Pages Generator

To automatically generate GitLab Pages Docs, create a 'mkdocs.yml' at the root of the project and add the following to '.gitlab-ci.yml'

--8<-- "docs/mkdocs.md"

GitLab-CI env variables can be passed to mkdocs.yml like so:

``` yaml
repo_name: !!python/object/apply:os.getenv ["CI_PROJECT_PATH"]
```

## Mkdocs

[mkdocs](https://www.mkdocs.org)

### Misc

<https://stackoverflow.com/questions/49978926/concatenate-multiple-markdown-files-using-pandoc-on-windows>
