<h1 align="center">KITPro</h1>

<p align="center"><strong>Practical technology for digital ownership.</strong></p>

<p align="center">
  KITPro builds open-source software and infrastructure that help people take control of their servers, data, and digital lives.
</p>

<p align="center">
  <a href="https://kitpro.us">Website</a> &bull;
  <a href="https://github.com/orgs/KITProHQ/repositories">Projects</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/tree/main/docs">Documentation</a>
</p>

## Our mission

The systems people depend on should remain understandable and useful to the people who own them. KITPro exists to make self-hosting and personal infrastructure more approachable without taking control away from the user.

We build around choice, not opposition to every cloud service. Local operation, open-source components, and accessible system boundaries reduce unnecessary dependence on any single provider. Our goal is simple: if KITPro disappeared tomorrow, users should still own their data and be able to administer their systems.

## What we build

KITPro's work centers on practical tools for:

- Self-hosting and server management
- Local-first infrastructure
- Linux-based systems with familiar tools underneath
- Privacy-respecting personal infrastructure
- User-owned services and data

These areas describe the organization's technical direction. They do not represent a list of released products.

## Projects

### KITPro Server

KITPro Server is the first major open-source project from KITPro. It is a local-first control panel for installing and operating a trusted set of self-hosted applications on your own Linux server.

The public alpha provides a browser interface for application installation, health, access, updates, storage, and hardware status. Applications start private, managed data survives container recreation, and standard Linux and container tools remain available underneath.

> [!WARNING]
> KITPro Server is alpha software. Review the [support matrix](https://github.com/KITProHQ/kitpro/blob/main/docs/support-matrix.md) and [known limitations](https://github.com/KITProHQ/kitpro/blob/main/docs/release/known-limitations.md) before relying on it for important data.

<p align="center">
  <img src="./assets/kitpro-server-dashboard.png" width="900" alt="KITPro Server dashboard showing server health and installed applications">
</p>

<p align="center">
  <a href="https://kitpro.us/server">Product page</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro">Repository</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/blob/main/docs/release/quickstart.md">Get started</a> &bull;
  <a href="https://github.com/KITProHQ/kitpro/releases">Releases</a>
</p>

The public alpha supports Debian 13, Ubuntu 26.04 LTS, and fully updated Arch Linux within the documented runtime boundaries. Rocky Linux 10 remains **Experimental** and is not part of the normal supported baseline.

## Principles

- **Ownership.** Users should control their infrastructure, data, and operational choices.
- **Open by default.** Favor open-source components, open standards, and systems that people can inspect.
- **No lock-in.** Simplify infrastructure without making continued operation depend on KITPro.
- **Approachable technology.** Help people begin without requiring prior expertise in Linux, containers, networking, or infrastructure.
- **Local first.** Keep core operation available on infrastructure the user controls without an unnecessary hosted dependency.
- **Standard underneath.** Build on established technologies and keep the underlying system accessible whenever practical.

## Open source

KITPro develops its current software openly on GitHub. KITPro Server is available under the [Apache License 2.0](https://github.com/KITProHQ/kitpro/blob/main/LICENSE), with architecture, security boundaries, release notes, and development history available in its repository.

## Get involved

- Browse the [KITProHQ repositories](https://github.com/orgs/KITProHQ/repositories).
- Report a KITPro Server bug or suggest an improvement through [GitHub Issues](https://github.com/KITProHQ/kitpro/issues).
- Read the [contribution guide](https://github.com/KITProHQ/kitpro/blob/main/CONTRIBUTING.md) before submitting a change to KITPro Server.
