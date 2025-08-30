# Shared Github Actions

## Code Checks (lint-if-changed + phpcs)

Runs a lint command only if files matching specified extensions have changed. Supports custom lint commands and optional Bun setup.

Checks for changes in PHP files and runs PHP CodeSniffer if changes are detected. Skips Composer install if `composer.json` is missing.

## Playwright Tests

Runs Playwright end-to-end tests in a specified environment using a provided npm script. Supports job timeouts and caches npm dependencies.

## Deploy & Release

Builds project assets (if specified) and deploys them to GitHub Releases. Supports custom asset folder and plugin file names, and cancels previous runs for the same branch.

# Changelog

## v1.0.0 - [August 30, 2025]

-   Init actions!
