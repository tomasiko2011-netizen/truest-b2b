# Graph Report - .  (2026-06-11)

## Corpus Check
- Corpus is ~4,743 words - fits in a single context window. You may not need a graph.

## Summary
- 11 nodes · 8 edges · 3 communities (2 shown, 1 thin omitted)
- Extraction: 88% EXTRACTED · 12% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Landing Page Sections and CI|Landing Page Sections and CI]]
- [[_COMMUNITY_Package Manifest|Package Manifest]]
- [[_COMMUNITY_Vercel Routing Config|Vercel Routing Config]]

## God Nodes (most connected - your core abstractions)
1. `Truest B2B Corporate Solutions` - 4 edges
2. `private` - 1 edges
3. `rewrites` - 1 edges
4. `ERP System` - 1 edges
5. `Electronic Document Management (EDO)` - 1 edges
6. `AutoCAD DXF Generation` - 1 edges
7. `CI Check Workflow` - 1 edges

## Surprising Connections (you probably didn't know these)
- `CI Check Workflow` --references--> `Truest B2B Corporate Solutions`  [INFERRED]
  .github/workflows/ci.yml → public/index.html

## Import Cycles
- None detected.

## Communities (3 total, 1 thin omitted)

### Community 0 - "Landing Page Sections and CI"
Cohesion: 0.40
Nodes (5): AutoCAD DXF Generation, Electronic Document Management (EDO), ERP System, Truest B2B Corporate Solutions, CI Check Workflow

### Community 1 - "Package Manifest"
Cohesion: 0.50
Nodes (3): name, private, version

## Knowledge Gaps
- **8 isolated node(s):** `name`, `version`, `private`, `rewrites`, `ERP System` (+3 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `name`, `version`, `private` to the rest of the system?**
  _8 weakly-connected nodes found - possible documentation gaps or missing edges._