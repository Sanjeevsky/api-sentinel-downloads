# Getting Started with API Sentinel

This guide is for the first 10 to 15 minutes with API Sentinel.

## What API Sentinel Is Best At

API Sentinel is designed for developers who want a local-first API client for:

- REST API testing
- request replay and debugging
- collections and environments
- response inspection
- repeatable request workflows

If you are coming from Postman, Insomnia, Thunder Client, or another HTTP client, the easiest way to begin is to send one request, save it, add an environment, and then explore the response and automation features from there.

## First Run Path

### 1. Open the App

When API Sentinel opens, focus on three areas:

- left sidebar: collections and history
- center composer: request building
- right/response side: response analysis and related tools

### 2. Create or Import Your First Request

The fastest options are:

- paste a plain URL into the request bar
- paste a complete cURL command into the request bar to import method, headers, and body
- create a request from a template if you want a prebuilt scaffold

### 3. Set Request Details

Before sending:

- choose the HTTP method
- add query params if needed
- add headers and auth
- choose the correct body mode if the endpoint expects a payload

Common body choices:

- JSON for most REST APIs
- form-data for uploads
- GraphQL for query/mutation requests

### 4. Send the Request

After sending, move directly to the response viewer.

Useful response tabs:

- body
- JSON tree
- headers
- cookies
- timeline
- tests, when assertions are present

### 5. Save the Request into a Collection

Once the request is useful, save it into a collection so it becomes part of a repeatable workflow.

Good collection organization patterns:

- one collection per service
- one collection per feature area
- one collection per integration

### 6. Add an Environment

Use environments when your base URL, tokens, or IDs change across local, staging, and production-like systems.

Typical variables:

- `BASE_URL`
- `ACCESS_TOKEN`
- `ORG_ID`
- `USER_ID`

### 7. Add Tests or Save a Snapshot

When a response matters long-term:

- add test scripts to assert important fields or status codes
- save a snapshot if you want a reusable response baseline

This is especially helpful for smoke tests, response drift checks, and regression validation.

## Where to Go for Common Tasks

| Task | Best Place in the App |
| --- | --- |
| Import cURL | URL bar |
| Organize saved requests | Sidebar collections |
| Reopen something you just ran | History |
| Change base URLs and tokens | Environments |
| Inspect headers and timing | Response viewer |
| Save a regression baseline | Snapshot tools |
| Chain several requests | Flows |
| Simulate missing backend endpoints | Mock server |
| Stress an endpoint | Load testing |
| Run quick security checks | Security tools |
| Work with WebSocket or SSE | Protocol composers |
| Capture and inspect traffic | Proxy capture |

## Recommended Learning Order

To avoid overload, learn the product in this sequence:

1. Request composer
2. Collections
3. Environments
4. Response viewer
5. Tests and snapshots
6. Collection runner
7. Mock server
8. Load testing and security tools
9. Flows and advanced protocol composers

## Good First Workflows

### Daily REST Workflow

1. Paste URL or cURL
2. Add auth and body
3. Send request
4. Inspect response
5. Save request to a collection

### Team API Review Workflow

1. Save requests into a collection
2. Attach an environment
3. Add tests
4. Save snapshots
5. Share release notes and docs from the public repository

### Frontend Integration Workflow

1. Build request
2. Save sample responses
3. Create mock routes
4. Compare live vs mocked responses

## When to Use Advanced Tools

Open the advanced areas only when the use case is clear:

- use mock server for frontend and demo workflows
- use load testing for concurrency and latency exploration
- use security tools for lightweight testing passes
- use flows when values must move between requests
- use protocol composers when the API is not plain REST

## Next Docs

After this guide, continue with:

- [Feature Overview](./FEATURES.md)
- [README](../README.md)
