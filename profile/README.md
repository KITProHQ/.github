<p align="center">
  <img src="./assets/kitpro-logo.png" width="112" alt="KITPro logo">
</p>

<h1 align="center">KITPro Server</h1>

<p align="center"><strong>Self-hosting, simplified.</strong></p>

<p align="center">Your server. Your data. Your control.</p>

<p align="center">
  A local-first control panel for installing and managing trusted self-hosted applications on your own Linux server.
</p>

<p align="center">
  <a href="https://kitpro.us/server">Website</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/blob/main/docs/release/quickstart.md">Get started</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/releases">Releases</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/tree/main/docs">Documentation</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/issues">Issues</a>
</p>

> [!WARNING]
> KITPro Server is alpha software. Review the [support matrix](https://github.com/KITProHQ/kitpro/blob/main/docs/support-matrix.md) and [known limitations](https://github.com/KITProHQ/kitpro/blob/main/docs/release/known-limitations.md) before relying on it for important data.

<p align="center">
  <img src="./assets/kitpro-server-dashboard.png" width="1200" alt="KITPro Server dashboard showing server health and installed applications">
</p>

## What is KITPro?

KITPro is an open-source project focused on making self-hosting more approachable. KITPro Server gives common server tasks a clear browser workflow while the Linux host, application data, and infrastructure remain under your control.

Standard Linux and container tools still run underneath. KITPro handles their repetitive details through reviewed workflows, so you do not need to become a Docker, networking, or storage expert before running useful services.

## Why KITPro?

Self-hosting often asks people to understand images, volumes, ports, credentials, updates, permissions, and recovery before they can use their first application. KITPro turns those concerns into bounded operations with visible status and explicit choices.

The project stays local-first. Core administration runs on your server without a required KITPro cloud account, telemetry service, or cloud control plane.

## KITPro Server

KITPro Server currently provides:

- A browser dashboard for first-run setup, application installation, health, access, updates, storage, and hardware status.
- A trusted catalog of 15 reviewed self-hosted applications with digest-pinned images.
- Application controls for install, start, stop, recreate, update, and uninstall workflows.
- Private-by-default services with explicit **This server only** and **Local network** access modes.
- Persistent managed data that survives container recreation.
- Administrator-approved local or host-mounted storage through typed read-only and read-write slots.
- A constrained privileged helper that independently validates host operations while the web interface and API remain unprivileged.

Read the [application catalog](https://github.com/KITProHQ/kitpro/blob/main/docs/application-catalog.md), [architecture](https://github.com/KITProHQ/kitpro/blob/main/docs/architecture.md), and [security model](https://github.com/KITProHQ/kitpro/blob/main/docs/security/current-security-boundary.md) for the full boundaries.

## Get started

1. Check the [platform support matrix](https://github.com/KITProHQ/kitpro/blob/main/docs/support-matrix.md) and [known limitations](https://github.com/KITProHQ/kitpro/blob/main/docs/release/known-limitations.md).
2. Download the package and matching checksums from the [GitHub releases page](https://github.com/KITProHQ/kitpro/releases).
3. Follow the [public alpha quickstart](https://github.com/KITProHQ/kitpro/blob/main/docs/release/quickstart.md) for Debian, Ubuntu, or Arch Linux.

Release notes, the release manifest, and checksums on the release page are authoritative for downloaded packages.

## Platform support

| Platform | Status | Package and runtime boundary |
| --- | --- | --- |
| Debian 13 amd64 | Supported | `.deb`, rootful Docker, enforcing AppArmor |
| Ubuntu 26.04 LTS amd64 | Supported | `.deb`, rootful Docker, enforcing AppArmor |
| Arch Linux x86_64 | Supported | `.pkg.tar.zst`, `linux-lts`, fully updated official repositories, rootful Docker, enforcing AppArmor |
| Rocky Linux 10 amd64 | **Experimental** | Podman 5, Quadlet, SELinux Enforcing. [Experimental preview](https://kitpro.us/server/install/rocky). No supported Rocky release is published. |

Rocky Linux 10 is not part of the normal supported production baseline. Its installation path remains experimental while external testing continues.

## What's included

- **Application management:** A focused catalog for monitoring, productivity, home automation, documents, local AI, media, and file access.
- **Storage and data:** Installation-owned persistent data plus approved external storage for supported media and file applications.
- **Access controls:** Private, server-only, or exact-address local network exposure. KITPro does not provide automatic Internet exposure.
- **Host boundaries:** Trusted application definitions, immutable image digests, typed storage and device access, and fail-closed validation.

## Open source and contributing

KITPro Server is developed openly under the [Apache License 2.0](https://github.com/KITProHQ/kitpro/blob/main/LICENSE).

Start with the [KITPro Server repository](https://github.com/KITProHQ/kitpro). Read the [contribution guide](https://github.com/KITProHQ/kitpro/blob/main/CONTRIBUTING.md) before submitting a change, or use [GitHub Issues](https://github.com/KITProHQ/kitpro/issues) to report a bug or suggest an improvement.
