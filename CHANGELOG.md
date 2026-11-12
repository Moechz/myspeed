# Changelog

All notable user-visible changes to the MySpeed TOS application package.

## 1.0.9-3 — 2026-11-12

### Changed
- Icon: replaced the letter monogram with a functional vector mark that describes what the app does (the upstream project does not publish a compliant SVG).

## 1.0.9-2 — 2026-11-12

### Changed
- Icon: replaced the letter monogram with a functional vector mark that describes what the app does (the upstream project does not publish a compliant SVG).

## 1.0.9-1 — 2026-11-11

### Added
- First release. MySpeed (`germannewsmaker/myspeed:1.0.9`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8083 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/myspeeddocker/`.
