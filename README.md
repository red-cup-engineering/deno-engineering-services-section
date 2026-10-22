# Deno services section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This is the authoritative home for live services whose execution, tooling, or
deployment contract depends on Deno.

Deno is a runtime and toolchain for JavaScript and TypeScript. In this
repository it is a sibling concern to Node.js within the broader JavaScript
ecosystem: service capability determines the outer hierarchy, while this
section owns the Deno-specific implementation and operating knowledge.

## Holdings

- `services/deno-deploy-free-compute-provider/` supplies authenticated,
  bounded edge computation on Deno Deploy.
- `services/jsnode-function-movement-cloud-provider/` supplies ephemeral Deno
  execution for deterministic JavaScript function movement.

## Boundaries

- The repository-root `deno.jsonc` and `deno.lock` coordinate the entire
  workspace and remain at repository root.
- General JavaScript and Node.js services remain direct holdings of the parent
  `javascript-engineering-services-section`.
- Historical records keep their original paths as evidence; they do not define
  the current service topology.
