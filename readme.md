<p align="center">
  <img src="pmxtools.png" alt="pmxtools" width="120" />
</p>

<h1 align="center">pmxtools-release</h1>

<p align="center">
  Official public releases of pmxtools — the desktop app for monitoring and managing Proxmox VE<br/>
  <sub>No source here — pmxtools is closed-source</sub>
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/vlT-vl/pmxtools-release?display_name=tag&sort=date&style=flat-square&label=latest" alt="latest release"/></a>
  <img src="https://img.shields.io/badge/source-private-critical?style=flat-square" alt="source-private"/>
  <img src="https://img.shields.io/badge/license-proprietary-critical?style=flat-square" alt="license"/>
</p>

---

## Overview

**pmxtools** is a native desktop application (Go + React) that gives you a graphical control panel for monitoring and managing Proxmox VE infrastructures.

This repository (`pmxtools-release`) is the official public place to download pmxtools. It contains **no application source code**: it only publishes the release builds of the desktop app, each with its changelog.

---

## Downloads

Every release is published in the [Releases](../../releases) section (the badge above always shows the latest tag), with one zipped build per platform:

| Platform | Artifact |
|---|---|
| macOS (Apple Silicon) | `build-darwin-arm64.zip` |
| macOS (Intel) | `build-darwin-amd64.zip` |
| Windows (amd64) | `build-windows-amd64.zip` |
| Linux (amd64) | `build-linux-amd64.zip` |
| Linux (arm64) | `build-linux-arm64.zip` |

Release tags follow the format `v<version>-<build>`, and each release carries its own changelog in the release notes.

---

Copyright © 2026 vlT di Veronesi Lorenzo. All rights reserved.
