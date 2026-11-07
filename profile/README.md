# KITPro

Practical technology for digital ownership.

KITPro builds open-source software for people who want to understand and
administer their own infrastructure. We focus on Linux servers, self-hosted
applications, and systems that keep users in control of their data.

[Website](https://kitpro.us) · [Blog](https://kitpro.us/blog) · [Documentation](https://github.com/KITProHQ/kitpro-linux/tree/main/docs) · [Releases](https://github.com/KITProHQ/kitpro-linux/releases) · [Public projects](https://github.com/orgs/KITProHQ/repositories)

## KITPro Linux Server · Released

An Arch-derived server distribution with controlled package promotion,
guided installation, and recovery tools. **Version 1.1.0** was published on
November 1, 2026, using generation `1.1-g0001`. Support runs through November 1,
2027. Version 1.0 remains available under its original terms.

The release requires x86_64 hardware and UEFI with Secure Boot disabled.
General dual boot, RAID, and advanced multi-disk configurations are not
qualified. Read the requirements and limitations before installing.

[Product page](https://kitpro.us/linux-server) · [1.1.0 release and downloads](https://github.com/KITProHQ/kitpro-linux/releases/tag/v1.1.0) · [Source and documentation](https://github.com/KITProHQ/kitpro-linux)

## KITPro Installer · Included component

Installer **1.2.0** is included in Linux Server 1.1.0. It provides the guided
installation interface within that qualified release. This component version
does not represent a separate public Installer release.

[Linux Server installation guide](https://github.com/KITProHQ/kitpro-linux/blob/main/docs/1.1/installation-guide.md)

## KITPro Console · In development

A self-hosted web console for Linux server administration and Docker
application management. Console is in active development, with no stable
Console release. It is optional and not installed by default in Linux Server
1.1.

Console is the presentation name announced on November 2, 2026 for the former
KITPro Server project. Historical alpha.11 through alpha.15 releases keep that
earlier name. Packages, services, paths, and APIs retain their `kitpro-server`
technical identities.

[Project and documentation](https://github.com/KITProHQ/kitpro) · [Historical alpha releases](https://github.com/KITProHQ/kitpro/releases)

## Project principles

- Keep users in control of their infrastructure and data.
- Use familiar Linux tools and inspectable source.
- Document release scope, qualification evidence, and recovery limits.
- Make administration understandable through clear documentation.

Public repositories provide source, licenses, and release history. Check each
project's license and contribution instructions before using or changing code.

## Support KITPro

No active GitHub Sponsors destination is currently published for KITPro.
You can support the projects by reporting reproducible bugs, improving
documentation, and contributing within each repository's guidelines. Include
the release and platform in issue reports so they can be assessed against the
documented scope.
