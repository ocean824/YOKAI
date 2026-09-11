# CodeSpring → Ludus Handoff

CodeSpring expands governing game requirements into atomic Unreal work packages; Ludus executes them inside Unreal.

## Required package
Each work package must include: stable WP ID; requirement IDs; objective/non-goals; dependencies; governing docs; task-specific specs; affected expected assets/systems; subsystem owner; acceptance criteria; validation/Gauntlet requirements; risk; rollback/migration notes.

## Context Manifest
```yaml
work_package: YOKAI-WP-XXXX
requirements: []
governing: [XYRA_UNREAL_PROTOCOL.md, GAME_DESIGN_BIBLE.md, PRODUCTION_SYSTEMS.md, UNREAL_BUILD.md]
task_specific: []
targets: []
dependencies: []
acceptance: []
evidence: []
```

Sync governing and relevant CodeSpring Markdown into Unreal `Docs/XYRA/`; Ludus automatically learns durable project documents. Keep full corpus indexed in GitHub/CodeSpring, but copy/select only relevant active package context where possible.

## Source control
One scoped branch/worktree per package when practical: `feature/YOKAI-WP-XXXX` → develop → staging → main. Unreal binary assets should use appropriate Git LFS strategy. Do not commit Binaries, DerivedDataCache, Intermediate or Saved.

## Closeout
Ludus returns evidence; CodeSpring/XYRA reviewer maps evidence to acceptance criteria and opens fixes/findings before promotion.