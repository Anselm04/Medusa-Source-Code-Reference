# Direct upstream source research — medusa

**Permanent reference access rule:** This repository and its pinned upstream source are two parts of the same engineering research reference. Before making architectural decisions, examine both the locally archived source AND any omitted source at its original pinned upstream location.

## Research links

- [Local source reference repository](https://github.com/Anselm04/Medusa-Source-Code-Reference)
- [Original upstream tree at the exact pinned commit](https://github.com/medusajs/medusa/tree/01de0be27a7c228795d5cfc31662ca144781fbfc)
- [Every one of the 265 omitted files, linked individually](../upstream-gap-index/medusa-missing-paths.md)
- [Machine-readable missing-path manifest with original Git identity](../verified-source-audit/medusa-main-delta.json)
- [Original licence and attribution](../LICENSE)

## Coverage and engineering instruction

The local archive intentionally omits **265 Git-tracked paths**: enterprise-licensed implementation files. They remain part of our research inventory through direct source links; **they are not present as locally uploaded source files**. The upstream URLs refer to the exact pinned revision rather than a moving branch head.

When investigating a subsystem, follow the omitted-file index to inspect the original implementation where accessible and permitted. Record its architecture, interfaces, data flow, trust boundaries, and testing behaviour; design and implement original TrillionAI functionality instead of blindly copying implementation code. Record which evidence comes from the local repository versus which was directly inspected upstream. If a link becomes unavailable, mark it unavailable rather than claiming the original contents are stored locally.

**Never republish credentials or bypass licence restrictions.** This reference note grants no additional rights to copy or redistribute third-party source. For potentially sensitive fixtures, use safely redacted structural notes or synthetic examples.

This document exists to prevent engineering decisions based on a partial repository without realising that the separately linked upstream source also needs to be consulted.
