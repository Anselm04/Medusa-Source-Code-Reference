# Medusa — TrillionAI source-code reference

Independent research reference for [medusajs/medusa](https://github.com/medusajs/medusa), focused on commerce architecture, payment and order workflows, API/event patterns, and reliability engineering relevant to AppForge, TrillionAI Marketing and Manager.

## Licence-aware source snapshot

Medusa's current root `LICENSE` specifies MIT for the community source **except** proprietary Enterprise Materials explicitly enumerated in its `ENTERPRISE-LICENSE.md`. RBAC and SSO implementation files and directories listed in that licence require a separate commercial agreement. The import workflow excludes those exact tracked paths from the public archive while preserving both original licence notices.

- Original upstream: `medusajs/medusa`
- Original upstream commit: `01de0be27a7c228795d5cfc31662ca144781fbfc`
- Original upstream Git tree: `f832114f0e597e1480c74630d954a4db22ded5ae`
- Proposed snapshot branch: [`medusa-upstream-snapshot`](https://github.com/Anselm04/Medusa-Source-Code-Reference/tree/medusa-upstream-snapshot/upstream)
- [Automated licence-filtered import and remote verification](https://github.com/Anselm04/Medusa-Source-Code-Reference/actions/workflows/import-medusa-source.yml)

The snapshot is not a full verbatim mirror: enterprise material is deliberately omitted. It should only be marked **verified** after the import workflow confirms the filtered tree was uploaded and matches the recorded filtered local tree.

## Engineering separation

The imported source is a reference for lawful technical study, not reusable commercial product code by default. Research patterns, then independently implement and test original TrillionAI Flutter/Node.js solutions. Do not merge this reference branch into TrillionAI production code, run imported application dependencies, or activate paid cloud services. Preserving a Git tree does not preserve complete history, private infrastructure or external binary/submodule payloads.
