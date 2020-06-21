path: tree/master
source: templates/default.yml

# Quickstart

Add this clause to your .gitlab-ci.yml

--8<-- "misc/quick-start.md"

!!! info "This is a general setting with sane defaults and autodetection linting."

Includes:

- [X] Auto-detect linting for common formats
- [X] SAST Testing
- [X] Pushover and Healthcheck notifications (Won't cause pipeline failure)
- [X] Automatic Gitlab Pages Deployment

!!! info "Linters will not cause pipeline failure (but will provide lint suggestions)"