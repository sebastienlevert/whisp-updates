# Whisp for Windows

This public repository is the binary-only distribution and stable update feed for Whisp. The application source remains private.

Download the latest **Whisp-win-x64-Setup.exe** from Releases. Whisp installs per-user, starts paused, and stores user-managed models, transcripts, settings, and voice profiles outside the install directory under `%USERPROFILE%\.whisp`.

## Trust and provenance

Releases include SHA-256 provenance generated from the private source commit and tree used for packaging. Velopack metadata and package hashes are verified before an in-app update is staged.

Current development releases are **unsigned** because no trusted publisher certificate is available. Windows may show an unknown-publisher or SmartScreen warning. Do not bypass organizational security policy. A future production release should use a legitimate trusted signing identity such as Azure Artifact Signing.

This repository contains no application source, models, transcripts, settings, credentials, personal data, or debug logs.
