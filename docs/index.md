<!-- ![!Logo](images/logo.png){: style=“height:50px;width:50px”}

![!Logo](images/logo.png){: width=“400” } -->

# Modular GitLab-CI

## About

Customizable, stackable templates for a variety of functions specifically built for use in GitLab-CI pipelines.

## Benefits

- [X] Reduced code repetition
- [X] Faster pipeline development and runs
- [X] Pipeline debugging
- [X] Increased consistency among projects
- [X] Optimized performance
- [X] Pipelines can be altered and adapted quickly
- [X] Security (Vault Integration)

## How it works

In many cases, including functionality is as easy as an include clause in a project's `.gitlab-ci.yml`. These templates are designed to be simple, intuitive, and as auto-magical as possible.

!!! abstract "This library includes a wide range of functionality, and will be expanded over time."

### Example usage (shell linting)

To add a job to check shell scripting, add the following to your `.gitlab-ci.yml`

--8<-- "lint/shell/all.md"

### Stacking Templates

Templates can be combined to extend functionality.

Enabling both SAST scanning and yaml linting:

--8<-- "misc/stack-example.md"

## Quickstart

Getting started guide [here](quick_start.md).

## Guide

Check out examples of what can be achieved [here](examples.md).

## Reference

Detailed usage descriptions [here](about/changelog.md).

{{ read_csv('docs/test.csv') }}

!!! warning "This is a living document, and sometimes life is messy."
