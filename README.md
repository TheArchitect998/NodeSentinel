<p align="center">
  <img src="assets/brand/nodesentinel-logo.png" alt="NodeSentinel" width="560">
</p>

<p align="center">
  <strong>Self-hosted monitoring for Linux systems and containers.</strong>
</p>

<p align="center">
  <a href="https://nodesentinel.de"><strong>Website</strong></a>
  ·
  <a href="https://nodesentinel.de/en/docs/"><strong>Documentation</strong></a>
  ·
  <a href="https://github.com/TheArchitect998/NodeSentinel/releases"><strong>Releases</strong></a>
</p>

## Overview

NodeSentinel brings metrics, Docker status, security information, availability
checks, and notifications together in a single dashboard. Agents collect data
from monitored hosts, while all measurements and settings remain within your
own infrastructure.

The dashboard is available in English and German. This README links to the
English documentation; a German documentation version is also available.

## Who Is NodeSentinel For?

- Homelab operators and self-hosters
- Small server and Raspberry Pi environments
- Administrators of personal or small business Linux infrastructure
- Users who need lightweight monitoring without a mandatory cloud service or
  telemetry

Linux on **AMD64 and ARM64** is supported.

## Installation

Choose the installation method that fits your environment:

| Method | Best for | Guide |
| --- | --- | --- |
| **Docker Compose** | The fastest setup with prebuilt multi-architecture images | [Docker installation](https://nodesentinel.de/en/docs/docker/) |
| **Dockhand or Portainer** | Running and updating through an existing container web interface | [Stack installation](https://nodesentinel.de/en/docs/docker/#dockhand-oder-portainer) |
| **Native with systemd** | Running as a Go binary directly on Linux hosts | [Native installation](https://nodesentinel.de/en/docs/nativ/) |

The recommended starting point is the [quick start guide](https://nodesentinel.de/en/docs/schnellstart/).

The dashboard serves its logo and shortcut icons from `frontend/icons/`. For a
native installation or update, keep this directory alongside
`frontend/index.html` and use the matching dashboard binary.

## Documentation

The complete, up-to-date documentation is maintained in the
[`nodesentinel-site`](https://github.com/TheArchitect998/nodesentinel-site)
repository and published at **https://nodesentinel.de/en/docs/**.

- [Quick start](https://nodesentinel.de/en/docs/schnellstart/)
- [Docker Compose](https://nodesentinel.de/en/docs/docker/)
- [Native installation](https://nodesentinel.de/en/docs/nativ/)
- [Configuration](https://nodesentinel.de/en/docs/konfiguration/)
- [Reverse proxy and HTTPS](https://nodesentinel.de/en/docs/reverse-proxy/)

## How NodeSentinel Is Made

AI coding assistants contribute to NodeSentinel's code, tests, and
documentation. I make the architectural and security decisions, review
the changes, and decide what gets released. Going forward, AI assistance
will be disclosed in commit co-author trailers.

I run NodeSentinel in my homelab and test every release there before
publishing.

To keep the project easy to review:

- The codebase is deliberately small: a Go dashboard and agent, SQLite,
  and a frontend without a framework.
- Releases are tested end to end on fresh machines across the Docker,
  native/systemd, and update paths.
- Security-relevant design choices and configuration guidance are
  documented in the [security documentation](https://nodesentinel.de/en/docs/sicherheit/)
  and [SECURITY.md](SECURITY.md).

Bug reports and ideas are welcome as GitHub issues. Security
vulnerabilities: please report privately (see SECURITY.md above).

## Version and Release Notes

**Current stable version: `v2.4.3`**

Version `v2.4.3` adds the new NodeSentinel logo and shortcut icons for browsers,
desktop, and iPhone home screens. Changes, known limitations, and previous
versions are available in the
[GitHub releases](https://github.com/TheArchitect998/NodeSentinel/releases)
and [version tags](https://github.com/TheArchitect998/NodeSentinel/tags).

## License

NodeSentinel is licensed under the [Apache License 2.0](LICENSE).
