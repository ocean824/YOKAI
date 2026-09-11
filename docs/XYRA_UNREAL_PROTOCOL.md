# XYRA Unreal Protocol — Ludus Execution Profile

This is the standing Unreal implementation constitution for Ludus AI.

## Authority
Ø current instruction > repository Build/Game contracts > GAME_DESIGN_BIBLE > PRODUCTION_SYSTEMS > UNREAL_BUILD > accepted ADRs > active CodeSpring work package/acceptance criteria > supporting specs > existing implementation.

## Loop
`REQUIREMENT → PLAN → IMPLEMENT → BUILD → VALIDATE → REVIEW → ATTACK → FIX → REVALIDATE → EVIDENCE → SOURCE CONTROL`.

## Start every work package
1. Resolve active Context Manifest and requirement IDs.
2. Read only relevant `/Docs/XYRA` documents plus actual project assets/code.
3. Identify affected Blueprints/C++/UMG/BT/EQS/Niagara/MetaSounds/Data Assets/Tables/levels/plugins.
4. Produce plan, ownership changes, tests and risks before mutation.
5. Escalate material requirement/canon/architecture conflicts.

## Foundation rule
Narrative Pro 2 + Ultra Game Template 1.3 are default shared Unreal foundation. Specialized Fab systems are accelerators. For overlapping Combat/Attributes/Inventory/Save/Quests/Dialogue/Interaction/Abilities/Input/Camera/Networking/AI/Progression, designate exactly one canonical owner or an explicit adapter boundary. Classify imported systems: KEEP, MODIFY, WRAP, REPLACE, REFERENCE_ONLY, REJECT.

## Engineering
Use C++ for canonical/testable/performance/network-authority logic where appropriate; Blueprint for authored content/presentation/rapid composition where appropriate. Never choose merely for agent convenience. No cloud/LLM dependency in realtime gameplay loops unless explicitly architected asynchronously.

## Ludus
Ludus may edit Blueprint, C++, UMG, BT/EQS, Niagara, MetaSounds, PCG, data and levels within approved scope. Use its plan/sub-agents for large bounded packages. Changes remain staged/reviewable. Git is canonical version control.

## Defects
Implementation→fix. Requirement→escalate. Architecture→ADR/change + re-Gauntlet. Test→change only when governing behavior proves it wrong. Environment→repair/rerun. Fab/provider→wrap/replace/degrade/document; provider blame does not close finding.

## Completion evidence
Requirements satisfied; assets/files changed; Blueprint/C++ changes; plugins/templates affected; compile/test/PIE/package results; logs/errors; save/network/performance checks applicable; adversarial cases; known limitations/findings; Git status/commit/PR reference.

No critical unresolved finding = PASS.