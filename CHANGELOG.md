# Changelog

All notable changes to this project will be documented in this file.

## [0.7.1]() (2025-07-21)

### Features

* Update to use c0x12c/monitors/datadog version 1.0.0
* Add override_default_message to change default alert messages

## [0.7.0]() (2025-07-10)

### Breaking changes

* Modify the Datadog restart monitor to use the change() function, following the Datadog example.

## [0.6.0]() (2024-06-20)

### Changes

- Update Datadog Monitor Module Source to Terraform Registry.

## [0.5.1]() (2024-04-24)

### Breaking changes

* Modify the Datadog restart monitor to use the diff function, which captures only new restart events. When a pod restarts, the query returns a value of 1, and it falls back to 0 if no further restarts occur.

## [0.1.36]() (2024-01-05)

### Features

* Initial commit with all the code
