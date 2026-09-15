# HoverEnglish Releases

Public distribution repository for **Hover English** Windows builds.

This repository contains downloadable release packages and the `latest.json` update manifest consumed by the application. Source code remains in the separate HoverEnglish repository.

## Update feed

`latest.json` is the stable manifest used by Hover English to check for application updates.

## Security

Release packages are accompanied by a SHA-256 value in `latest.json`. The updater verifies this hash before installing a downloaded package.
