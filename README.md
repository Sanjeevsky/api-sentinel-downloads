# API Sentinel — Lightweight Postman Alternative for API Testing

API Sentinel is a developer-focused desktop API client for REST API testing, request history, collections, environments, and local-first workflows. This repository is the public download and product page for API Sentinel. It does not contain application source code.

If you are searching for a Postman alternative, Insomnia alternative, Thunder Client alternative, or a desktop API client for API testing, this repository is where you can read about the product and download the latest installers from GitHub Releases.

## Start Here

If this is your first time with API Sentinel, use these docs first:

- [Getting Started Guide](./docs/GETTING_STARTED.md)
- [Feature Overview](./docs/FEATURES.md)

Fast path for new users:

1. Download the installer for your platform.
2. Launch API Sentinel with no account setup required.
3. Paste a URL or full cURL command into the request bar.
4. Save the request into a collection and attach an environment.
5. Inspect the response, add tests, and save a snapshot if the result should become a baseline.
6. Open advanced tools only when you need them: mock server, load testing, security, flows, docs, proxy capture, and real-time protocol composers.

## Download

- Latest release: [Download API Sentinel from GitHub Releases](https://github.com/Sanjeevsky/api-sentinel-downloads/releases/latest)
- All releases: [View release history](https://github.com/Sanjeevsky/api-sentinel-downloads/releases)
- Current public release: `v0.0.1`

Each release will include platform installers such as:

- Windows: `.exe` for `x64`
- macOS: `.dmg` for Intel and Apple Silicon
- Linux: `.AppImage` for `x64` and `arm64`

## Why API Sentinel

API Sentinel is built for developers who want a fast API client without unnecessary friction. It is designed for local-first use, API exploration, request replay, environment-based testing, and day-to-day REST workflows.

Core positioning keywords, used honestly:

- Postman alternative
- API client
- REST client
- API testing tool
- HTTP client
- Insomnia alternative
- Thunder Client alternative
- desktop API client

Note: if you are specifically looking for an open source Postman alternative, API Sentinel is not open source. The source code remains private. This public repository exists for downloads, documentation, release notes, and trust material.

## Installation

### Windows (`.exe`)

1. Open the [latest release page](https://github.com/Sanjeevsky/api-sentinel-downloads/releases/latest).
2. Download the Windows installer file ending in `.exe`.
3. Run the installer.
4. If Windows SmartScreen appears, verify the publisher and checksum, then continue if appropriate for your environment.
5. Launch API Sentinel from the Start menu or desktop shortcut.

### macOS (`.dmg`)

1. Open the [latest release page](https://github.com/Sanjeevsky/api-sentinel-downloads/releases/latest).
2. Download the macOS installer file ending in `.dmg`.
3. Open the disk image and drag API Sentinel into `Applications`.
4. On first launch, macOS may ask you to confirm opening an app downloaded from the internet.
5. Launch API Sentinel from `Applications`.

### Linux (`.AppImage`)

1. Open the [latest release page](https://github.com/Sanjeevsky/api-sentinel-downloads/releases/latest).
2. Download the `.AppImage` that matches your Linux architecture.
3. Mark the file executable.
4. Run it directly.

Example:

```bash
chmod +x API-Sentinel.AppImage
./API-Sentinel.AppImage
```

## Feature Highlights

### Request Building

- URL bar with autocomplete and direct cURL import
- Structured editors for params, headers, auth, cookies, and variables
- Body modes for JSON, raw text, form-data, urlencoded, GraphQL, and binary uploads
- Request scripting, test scripting, and generated code snippets

### Response Analysis

- Pretty, raw, and JSON tree response views
- Headers, cookies, timeline, and searchable response inspection
- Snapshot saving, diffing, baseline assertions, and compare workflows
- Markdown-oriented response rendering and schema-style views

### Organization

- Collections, folders, request tabs, history, and templates
- Environments, collection variables, and local-first request storage
- Import/export support for common API client formats
- Backup, restore, and workspace-oriented tooling

### Advanced Tooling

- Collection runner and scheduled runs
- Mock server for local endpoint simulation
- Security scans and load testing
- Flows for chaining multi-step request workflows
- API documentation helpers and proxy capture
- WebSocket, SSE, Socket.IO, and MQTT composers
- Vault, certificates, and cookie management
- AI assistant and command palette for faster navigation

For the complete feature map, see [docs/FEATURES.md](./docs/FEATURES.md).

## Comparison

| Capability | API Sentinel | Postman | Insomnia | Thunder Client |
| --- | --- | --- | --- | --- |
| Desktop API client workflow | Yes | Yes | Yes | Limited to editor extension workflow |
| REST API testing | Yes | Yes | Yes | Yes |
| Collections | Yes | Yes | Yes | Yes |
| Environments | Yes | Yes | Yes | Yes |
| Local-first workflow | Yes | Mixed by plan and workflow | Mixed | Mostly editor-local |
| Forced login to get started | No | Often part of broader workflow | Varies | No |
| Public source code in this repo | No | No | No | No |

## Use Cases

API Sentinel is a strong fit for:

- Backend developers testing REST endpoints during implementation
- QA engineers running repeatable API testing flows
- Teams looking for a lightweight Postman alternative
- Developers who want a focused HTTP client without a large cloud-first workflow
- Engineers evaluating an Insomnia alternative or Thunder Client alternative for desktop use
- Anyone who wants a local-first API client for daily request/response work

## Quick Navigation Guide

Use this when you want to get to the right area quickly:

| Goal | Where to Start |
| --- | --- |
| Send a REST request fast | URL bar and request tabs |
| Import an existing cURL command | Paste directly into the URL bar |
| Organize requests by project | Collections in the left sidebar |
| Switch environments or variables | Header environment selector |
| Debug a response deeply | Response viewer tabs |
| Save a baseline for regression checks | Snapshot tools in the response viewer |
| Run repeated request flows | Collection runner or flows |
| Simulate backend behavior locally | Mock server |
| Test non-HTTP protocols | WebSocket, SSE, Socket.IO, or MQTT composers |
| Stress or scan an endpoint | Load testing or security tools |
| Generate docs or capture traffic | Docs tools and proxy capture |

## Screenshots

Add product screenshots to:

- `docs/screenshots/`

Suggested files to add later:

- `main-window.png`
- `request-composer.png`
- `response-viewer.png`
- `collections-and-environments.png`

After adding real screenshots, link them here in the README to improve trust, usability, and search visibility.

## Security and Trust

- API Sentinel is distributed as compiled desktop software.
- Source code is private and is not published in this repository.
- The product is designed for local-first workflows so request data, collections, and environments can remain on the user’s machine.
- No forced login is required to use the app.
- No telemetry is enabled by default unless explicitly documented in a release note or product documentation.
- Security concerns can be reported privately. See [SECURITY.md](./SECURITY.md).

## FAQ

### Is API Sentinel open source?

No. This public repository is a download and release page only. The application source code remains private.

### What kind of API client is API Sentinel?

It is a desktop API client and HTTP client focused on local-first API testing workflows.

### Where do I download the installers?

Use the [latest GitHub Release](https://github.com/Sanjeevsky/api-sentinel-downloads/releases/latest) to download the current `.exe` and `.dmg` files.

### Does this repository contain the application source code?

No. This repository is intentionally limited to release assets, documentation, changelog, policy files, and download guidance.

## Roadmap

Planned public-facing improvements:

- Add screenshots and walkthrough documentation
- Publish checksum files for every release
- Add feature overview pages under `docs/`
- Add release badges and version history improvements

Planned product-level improvements:

- Expanded API testing workflows
- Improved request collaboration and environment management
- Additional import/export and migration tooling
- Better onboarding for teams evaluating a new REST client

## Release Instructions

This section is intended for maintainers of the public download repository.

### 1. Build installers from the private source repository

Build API Sentinel from the private source repository on the appropriate platform:

- Windows build output: `.exe`
- macOS build output: `.dmg`
- Linux build outputs: `.AppImage` (and `.deb` when supported for that release)

### 2. Create a release in this public repository

Use a release title in this format:

`API Sentinel v1.0.0 — Modern API Testing Tool`

### 3. Upload release assets

Attach:

- Windows installer (`.exe`)
- macOS installer (`.dmg`)
- Linux installer (`.AppImage`)
- SHA256 checksum file or checksum values in the release notes

### 4. Publish checksums

Example checksum commands:

#### macOS / Linux

```bash
shasum -a 256 API-Sentinel-Setup.exe
shasum -a 256 API-Sentinel.dmg
shasum -a 256 API-Sentinel.AppImage
```

#### Windows PowerShell

```powershell
Get-FileHash .\API-Sentinel-Setup.exe -Algorithm SHA256
Get-FileHash .\API-Sentinel.dmg -Algorithm SHA256
```

Add the resulting hashes to the release notes so users can verify downloads.

## Repository Topics for SEO

Recommended GitHub topics:

- api-client
- rest-client
- api-testing
- http-client
- desktop-app
- developer-tools

## Support

- Bugs and feedback: open an issue in this repository
- Security issues: see [SECURITY.md](./SECURITY.md)
- Release notes: see [CHANGELOG.md](./CHANGELOG.md)

## License

API Sentinel is proprietary software. Review [LICENSE](./LICENSE) before downloading or using the application.
 postman-alternative
- api-client
- rest-client
- api-testing
- http-client
- desktop-app
- developer-tools
- insomnia-alternative
- thunder-client-alternative

## Support

- Bugs and feedback: open an issue in this repository
- Security issues: see [SECURITY.md](./SECURITY.md)
- Release notes: see [CHANGELOG.md](./CHANGELOG.md)

## License

API Sentinel is proprietary software. Review [LICENSE](./LICENSE) before downloading or using the application.
. Review [LICENSE](./LICENSE) before downloading or using the application.
