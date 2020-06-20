# Modular GitLab-CI

General, reusable, stackable templates for a variety of functions specifically built for use in GitLab-CI pipelines. 

## Benefits 

Reduced code repetition 
Faster development 
Pipeline debugging
increase consistency among projects
Optimized performance
Pipelines can be altered and adapted quickly

## How it works

In many cases, including functionality is as easy as an include clause in a project's .gitlab-ci.yml. These templates are designed to be simple, intuitive, and as auto-magical as possible.

!!! note
    This library includes a wide range of functionality, and will be expanded over time.

## Example

—8<— “lint/shell/all.yml”

## Todo

- [ ] vault integration
- [ ] extensions
  - [ ] ssh
  - [ ] terraform
  - [ ] packer
  - [ ] ansible

!!! note
    This documentation serves a double function. To document this repo, as well as to serve as internal reference for me as an aggregate for external reference links to the tools used by it.

!!! warning
    This is a living document, and sometimes life is messy.
