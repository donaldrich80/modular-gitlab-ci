---
title: Home
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
---

# Modular GitLab-CI

Versatile, stackable `.gitlab-ci.yml` templates for modular construction of GitLab-CI pipelines.

## Benefits

- [X] Reduced code repetition
- [X] Faster pipeline development and runs
- [X] Pipeline debugging options
- [X] Increased consistency among projects
- [X] Optimized performance
- [X] Pipelines can be altered and adapted quickly
- [X] Security (Vault Integration)

## How it works

In many cases, including functionality is as easy as an include clause in a project's `.gitlab-ci.yml`. These templates are designed to be simple, intuitive, and as auto-magical as possible.

### Example usage

#### Shell script linting

To add a job to check shell scripting, add the following to your `.gitlab-ci.yml`

--8<-- "lint/shell/all.md"

### Stacking Templates

Modules can be combined to extend functionality.

#### SAST scanning and YAML linting

--8<-- "misc/stack-example.md"

## Quickstart

Getting started guide [here](quick_start.md).

## Guide

Check out more basic module examples [here](examples.md).

## Reference

Detailed usage descriptions [here](about/changelog.md).
