<p align="center">
  <img src="assets/brand/nodesentinel-logo.png" alt="NodeSentinel" width="560">
</p>

<p align="center">
  <strong>Self-hosted monitoring for Linux systems and containers.</strong>
</p>

<p align="center">
  <a href="https://nodesentinel.de"><strong>Website</strong></a>
  ·
  <a href="https://nodesentinel.de/docs/"><strong>Documentation</strong></a>
  ·
  <a href="https://github.com/TheArchitect998/NodeSentinel/releases"><strong>Releases</strong></a>
</p>

## Overview

NodeSentinel brings metrics, Docker status, security information, availability
checks, and notifications together in a single dashboard. Agents collect data
from monitored hosts, while all measurements and settings remain within your
own infrastructure.

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
| **Docker Compose** | The fastest setup with prebuilt multi-architecture images | [Docker installation](https://nodesentinel.de/docs/docker/) |
| **Dockhand or Portainer** | Running and updating through an existing container web interface | [Stack installation](https://nodesentinel.de/docs/docker/#dockhand-oder-portainer) |
| **Native with systemd** | Running as a Go binary directly on Linux hosts | [Native installation](https://nodesentinel.de/docs/nativ/) |

The recommended starting point is the [quick start guide](https://nodesentinel.de/docs/schnellstart/).

The dashboard serves its logo and shortcut icons from `frontend/icons/`. For a
native installation or update, keep this directory alongside
`frontend/index.html` and use the matching dashboard binary.

## Documentation

The complete, up-to-date documentation is maintained in the
[`nodesentinel-site`](https://github.com/TheArchitect998/nodesentinel-site)
repository and published at **https://nodesentinel.de/docs/**.

- [Quick start](https://nodesentinel.de/docs/schnellstart/)
- [Docker Compose](https://nodesentinel.de/docs/docker/)
- [Native installation](https://nodesentinel.de/docs/nativ/)
- [Configuration](https://nodesentinel.de/docs/konfiguration/)
- [Reverse proxy and HTTPS](https://nodesentinel.de/docs/reverse-proxy/)

## Version and Release Notes

**Current stable version: `v2.4.3`**

Version `v2.4.3` adds the new NodeSentinel logo and shortcut icons for browsers,
desktop, and iPhone home screens. Changes, known limitations, and previous
versions are available in the
[GitHub releases](https://github.com/TheArchitect998/NodeSentinel/releases)
and [version tags](https://github.com/TheArchitect998/NodeSentinel/tags).

## License

NodeSentinel is licensed under the [Apache License 2.0](LICENSE).
