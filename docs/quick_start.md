path: tree/master
source: templates/default.yml

# Quickstart

## Public Repo with Documentation

!!! warning "mkdocs.yml required. Pipeline will fail without it."

Add this clause to your .gitlab-ci.yml

--8<-- "misc/quick-start.md"

!!! info "This is a general setting with sane defaults and autodetection linting."

Includes:

- [X] Auto-detect linting for common formats
- [X] SAST Testing
- [X] Pushover and Healthcheck notifications (Won't cause pipeline failure)
- [X] Automatic Gitlab Pages Deployment

## Private Repo (No Secret scanning)

SAST will cause pipeline failure if credintisls are found.

CREDSCAN: false

!!! info "Linters will not cause pipeline failure (but will provide lint suggestions)"

## No documention

GENERATE_DOCS: false