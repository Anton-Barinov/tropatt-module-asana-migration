# Миграция из Asana

Односторонняя миграция рабочих пространств, проектов, задач и связанных данных из Asana Cloud в TropaTT

A module for the [TropaTT](https://github.com/Anton-Barinov/TropaTT) self-hosted CRM and work platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Module info

| Field | Value |
|---|---|
| Module | `crm.asana-migration` |
| Version | `1.0.0` |
| Category | `migration` |
| Core | `>=1.0.0` |
| Required permissions | project.manage, task.manage |
| Author | [Anton Barinov](https://github.com/Anton-Barinov) |

## Installation

1. In TropaTT open **Admin → Modules → Install**.
2. Choose one of:
   - **Install from URL:** `https://github.com/Anton-Barinov/tropatt-module-asana-migration/releases/download/v1.0.0/crm.asana-migration-1.0.0.zip`
   - **Upload archive:** download the release `.zip` and upload it manually.
3. Activate the module and configure it in **Admin → Modules**.

> The archive contains the module files at its root (`manifest.json` + `api/` + `web/`).
> For manual install, place the files under `modules/crm.asana-migration/` of your TropaTT installation.

## Repository layout

- `upload/` — the module itself (what gets installed).
- `LICENSE` — MIT license.
- `SECURITY.md` — how to report vulnerabilities.

## Requirements

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

## License

[MIT](LICENSE) © Anton Barinov
