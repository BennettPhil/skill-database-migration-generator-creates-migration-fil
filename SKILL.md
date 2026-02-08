---
name: database-migration-generator-creates-migration-fil
description: A database migration generator that creates migration files from schema diff. Compare two database schema s...
version: 0.1.0
license: Apache-2.0
---

# database-migration-generator-creates-migration-fil

## Purpose

Use this skill to implement and operate: A database migration generator that creates migration files from schema diff. Compare two database schema states and produce up/down migration SQL with safety checks for data preservation..

## Instructions

1. Run `./scripts/run.sh --help` to inspect supported inputs.
2. Run `./scripts/run.sh "<target>"` to generate an execution plan and recommended checks.
3. Review the emitted checklist and adapt it for your repository or environment.

## Inputs

- A target name or path as the main argument.
- Optional `--context` text to provide extra constraints.

## Outputs

- A structured checklist printed to stdout.
- Exit code `0` on success and non-zero on invalid usage.

## Constraints

- This starter implementation is intentionally minimal.
- Tailor the generated checklist before using it in production workflows.
