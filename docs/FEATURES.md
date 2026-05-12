# API Sentinel Feature Overview

This guide is the fastest way to understand what API Sentinel provides and where to find each capability inside the app.

## Core Request Workflows

### Request Composer

Use the main composer when you want to build or modify an API request.

Available capabilities:

- URL entry with autocomplete
- direct cURL paste import
- HTTP method selection
- query parameter editor
- header editor with suggestions
- auth configuration
- cookies and variable-aware request building
- body editors for:
  - JSON and raw text
  - form-data
  - urlencoded payloads
  - GraphQL
  - binary/file payloads
- request settings for timeouts, redirects, SSL behavior, and related execution controls

### Scripting and Tests

For automated checks around a request:

- pre-request scripting
- test scripting
- console output capture
- test result summaries
- response assertions

### Code and Template Helpers

To speed up repeated work:

- reusable request templates
- clone and duplicate flows
- code generation from requests
- snippet-friendly request export paths

## Response Analysis

The response viewer is built for debugging and validation, not just raw output display.

Available views and tools:

- pretty body view
- raw body view
- JSON tree exploration
- headers view
- cookie inspection
- timing and timeline data
- response search
- download/export actions
- markdown-oriented rendering
- schema-style response presentation

## Regression and Comparison Tools

Use these features when you need repeatability or drift detection:

- save response snapshots
- mark expected baselines
- compare current vs saved responses
- compare snapshot vs snapshot
- inline pass/fail status in the response workflow

## Organization and Workspace Management

### Collections and Requests

Use the sidebar to structure work by service, team, feature, or environment.

Capabilities include:

- collections and nested organization
- inline rename actions
- request duplication
- collection duplication
- request templates
- request tabs for parallel work

### Environments and Variables

Use these when switching between local, staging, and production-like setups.

Available capabilities:

- environments
- collection variables
- variable toggles
- secret-aware value handling
- dynamic variables

### History and Recovery

For repeat work and rollback:

- request history
- time machine/history inspection
- backup and restore workflows
- global find and replace support

## Import and Export

API Sentinel includes migration-oriented tooling for teams moving from other API clients.

Supported import/export paths include:

- cURL
- OpenAPI
- HAR
- Common API client formats
- REST Client style inputs

## Execution and Automation

### Collection Runner

Use the runner when you want to execute multiple requests in sequence or repeatedly.

### Scheduled Runs

Use scheduled runs when you need recurring local automation.

### Flows

Use flows when one request depends on values produced by another request.

Typical scenarios:

- login then fetch profile
- create resource then validate retrieval
- chained smoke tests

## Protocol Support Beyond REST

API Sentinel is not limited to plain HTTP request-response work.

Additional protocol composers include:

- WebSocket
- Server-Sent Events (SSE)
- Socket.IO
- MQTT

## Testing, Security, and Reliability Tools

### Mock Server

Use the built-in mock server when frontend work or demos need stable local endpoints.

### Load Testing

Use load testing when you want to explore concurrency, duration, and latency behavior.

### Security Testing

Use the security tools for lightweight passive checks and engineer-friendly fuzzing passes.

### Proxy Capture

Use proxy capture when you want to inspect traffic and build requests from real network interactions.

## Documentation and Knowledge Tools

These tools help move from manual testing into reusable team artifacts.

- API documentation helpers
- markdown response views
- AI assistant
- command palette
- app tour and inline guides

## Local Trust and Operational Controls

API Sentinel is designed around local-first usage.

Supporting controls include:

- local-first data handling
- no forced login
- vault tooling
- certificate management
- cookie management
- workspace backups

## Best First Areas to Explore

If you are new to the product, start here in order:

1. Request composer
2. Collections and environments
3. Response viewer
4. Snapshots and tests
5. Mock server or collection runner
6. Load, security, flows, and protocol-specific tools
