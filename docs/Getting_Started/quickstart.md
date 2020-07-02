path: tree/master
source: templates/default.yml

# Quickstart

## Public Repo (with Pages)

This setting is intended for public repos with documentation, but can be customized.

Add this clause to your .gitlab-ci.yml

--8<-- "misc/quick-start.md"

!!! info "This is a general setting with sane defaults and autodetection linting."

Includes:

- [X] Auto-detect linting for common formats
- [X] SAST Testing
- [X] Pushover and Healthcheck notifications (Wont cause pipeline failure)
- [X] Automatic Gitlab Pages Deployment

### Disable SAST scan

SAST will cause pipeline failure if credintisls are found. To disable credential scan (for use in a private repo)

include:

--8<-- "variables/disable_sast.md"

!!! info "Linters will not cause pipeline failure (but will provide lint suggestions)"

### Disable Pages Generation

Documentation is enabled by default.

To disable Pages generation, this variable is required.

--8<-- "variables/disable_docs.md"

### Disable Linting

General linting is enabled by default.

To disable linting, this variable is required.

--8<-- "variables/disable_linting.md"

### Examples