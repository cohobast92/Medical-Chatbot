# Changelog


## 2026-02-05
- Remove hardcoded credentials and move to env-based configuration

## 2026-02-09
- Fix the ordering of middleware so auth runs before the handler

## 2026-02-11
- Bump dependency to get the security fix for the reported CVE

## 2026-02-19
- Refactor config loading into a separate module for better testability

## 2026-03-03
- Implement basic rate limiting to avoid overwhelming the downstream service

## 2026-03-05
- Improve the default config so it works out of the box for dev

## 2026-03-09
- Implement proper cleanup of resources when the process receives SIGTERM

## 2026-03-11
- Remove hardcoded credentials and move to env-based configuration
