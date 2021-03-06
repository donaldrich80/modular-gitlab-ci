---
title: Quickstart
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
path: tree/master
source: templates/default.yml
---

# Quickstart

## Usage

This is a general template with sane defaults and autodetection linting.

It's intended for public repos with documentation, but can be customized by disabling unwanted functions (see below)

To get started, and this clause to your `.gitlab-ci.yml`:

--8<-- "misc/quick-start.md"

!!! info ""

Includes:

- [x] Auto-detect linting for common formats
- [x] SAST Testing
- [x] Healthcheck pings
- [x] Pushover notifications on failure
- [x] Automatic Gitlab Pages Deployment

### Disable SAST scan

SAST will cause pipeline failure if credentials are detected.

To disable credential scan (for use in a private repo) include this variable:

--8<-- "variables/disable_sast.md"

### Disable Pages Generation

Documentation is enabled by default.

To disable Pages generation, this variable is required.

--8<-- "variables/disable_docs.md"

### Disable Linting

General linting is enabled by default.

To disable linting, this variable is required.

--8<-- "variables/disable_linting.md"

!!! info "Linters will not cause pipeline failure if errors are found (but will provide suggestions to correct them)"
