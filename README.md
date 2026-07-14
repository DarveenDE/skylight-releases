# Skylight releases

**Status: Beta 1 is in release-candidate preparation. No public Skylight binary is available yet.**

This repository is the official public distribution channel for Skylight. The first release will be published only after the exact macOS build has passed Developer ID signing, Hardened Runtime, notarization, Gatekeeper, checksum, source-license, and anonymous-download verification.

Until an actual release appears under [Releases](https://github.com/DarveenDE/skylight-releases/releases), any page or link claiming that Beta 1 is downloadable is premature.

## Planned Beta 1 payload

The `skylight-beta-1` prerelease will publish together:

- the notarized Apple Silicon DMG;
- matching dSYM crash symbols;
- SHA-256 checksums and a machine-readable release manifest;
- the exact corresponding source archive;
- GPL-3.0 and third-party license materials;
- release notes, installation, update, and rollback instructions.

Skylight Helper remains optional. Normal Sunshine or Moonshine streaming does not require it. Any Helper artifact will state its exact signing and intended-audience boundary.

## Safety

A valid Skylight release will not ask users to bypass Gatekeeper. Do not download builds from unlisted mirrors or disable macOS security controls to launch an artifact.

Project website: https://darveende.github.io/skylight/
