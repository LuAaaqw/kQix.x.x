# kQIx

**A Lua/Luau-oriented software toolchain for Windows.**

kQIx is an actively developed desktop project for preparing script-based projects for controlled distribution. It brings together a configurable processing workflow, build-time handling, runtime-oriented components, and diagnostic tooling under one application.

Public documentation intentionally stays at a high level. Internal design choices, processing stages, and implementation details are not described here.

> **Current public version:** `1.4.0`  
> **Status:** Active development  
> **Primary platform:** Windows x64

---

## Overview

kQIx is being developed with an emphasis on predictable output, configurable workflows, compatibility, and repeatable validation.

The project evolves continuously. Available options and behavior may differ between builds, and experimental work should not be treated as a stable public feature until it is included in a documented release.

## General direction

Development is focused on a small number of broad areas:

- **Workflow refinement** — improving the overall build and user experience.
- **Output quality** — keeping generated results consistent and practical to use.
- **Runtime reliability** — improving behavior across supported environments.
- **Diagnostics** — making failures and compatibility issues easier to investigate.
- **Performance** — measuring and reducing unnecessary overhead.

Specific implementation details are intentionally omitted from the public overview.

## Platform

- Windows desktop, x64.
- C++20 native components.
- Visual Studio 2022 project/solution support.
- Lua/Luau-oriented workflows; exact compatibility depends on the build and target environment.

Compatibility is validated incrementally. A feature being present in a development build does not automatically mean it is supported in every host or runtime.

## Releases

Official packages and release notes should be published through the GitHub **Releases** page.

Each release should include:

- public version number;
- supported platform and relevant requirements;
- a concise change summary;
- known limitations;
- verification notes;
- SHA-256 checksum for downloadable packages.

The current public version remains **1.4.0** until a newer release is formally published.

## Documentation

Public documentation will cover user-facing setup, general usage, compatibility notes, troubleshooting, and release history.

Internal architecture notes and implementation-specific material are maintained separately and are not part of this public overview.

## Reporting an issue

When opening an issue, include:

- kQIx version;
- Windows version;
- target runtime or environment;
- a short description of the expected and actual behavior;
- minimal reproduction steps;
- sanitized logs, where relevant.

Do not publish private scripts, account information, license data, credentials, tokens, or other sensitive material in public issues. Security-sensitive reports should be sent through a private reporting channel once one is configured.

## Security and limitations

kQIx is intended to make casual inspection and unauthorized modification more difficult. No client-side transformation or runtime process can guarantee that software is impossible to inspect, reproduce, intercept, or modify.

Use the project only with scripts and software you own or are authorized to process.

## License

A license has not yet been specified. Until a `LICENSE` file is added, no permissions beyond those provided by the applicable law should be assumed. In particular, public visibility alone does not grant permission to reuse, redistribute, modify, or commercially exploit the project.

## Disclaimer

kQIx is provided for software development, protection-oriented workflows, testing, and research. Compatibility and behavior are not guaranteed across every Lua/Luau runtime or third-party environment.
