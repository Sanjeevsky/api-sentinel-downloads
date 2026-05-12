# Changelog

All notable changes to the public release of API Sentinel will be documented in this file.

The format is inspired by Keep a Changelog and intended for human-readable release tracking.

## [v0.0.1] - 2026-05-12

### Added

- Initial public release of API Sentinel
- Desktop installer distribution through GitHub Releases
- Public release assets for Windows x64, macOS Intel and Apple Silicon, and Linux AppImage on x64 and arm64
- Support for REST API testing workflows
- Collections, environments, request history, templates, snapshots, and compare workflows
- GraphQL support, mock server, load testing, security helpers, and real-time protocol tooling
- Branded desktop application icons for packaged builds
- Improved mock server startup flow for development and Electron usage
- Expanded public documentation for API testing, mock server, load testing, and real-time protocol workflows
- macOS DMG downloads for Apple Silicon (`arm64`) and Intel (`x64`)

### Changed

- Established the public download repository for releases, trust documentation, and release notes
- Separated private source code from the public-facing distribution repository
- Repositioned public repository messaging around product capabilities instead of competitor-heavy keywords
- Added release download badges to improve public repository discoverability and trust
- Documented the current macOS first-launch approval flow for unsigned builds

### Fixed

- Mock server startup reliability when launched from the app workflow
- Build metadata for Linux packaging
