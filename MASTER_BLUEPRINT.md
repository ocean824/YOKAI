# YOKAI Master Blueprint

## Canon
One game design, two engine implementations. `GAME CANON → system contracts → Unreal implementation / AXIOM implementation`.

## Core systems
Player locomotion/camera; stamina/poise/health/status; melee/ranged/magic-style Yokai abilities; lock-on; dodge/parry/block; weapons; Divine Canvas actions; creature encounter/capture/bond; party/loadout; evolution branches; fusion/inheritance; elemental interactions; enemy/boss AI; quests/dialogue/world state; inventory/equipment/crafting; progression; exploration/traversal; checkpoints/death/recovery; save; UI/accessibility; audio; multiplayer/session/replication; analytics/dev/admin tooling.

## Divine Canvas
Must affect gameplay rather than be cosmetic: paint/reveal/restore/seal/cut/bridge/alter selected world states and interact with combat/Yokai abilities. Every power has authored constraints, feedback, save-state semantics and multiplayer authority rules.

## Creature contract
Data-driven species/variant/skills/stats/affinities/evolution/fusion tables. Fusion must define parent contribution, inherited skills/traits, rarity constraints, deterministic seed/audit where needed and anti-duplication rules for networked play.

## Unreal implementation
Narrative Pro 2 owns narrative/quest/dialogue unless evaluation proves another module materially superior. Ultra Game Template supplies general foundation. Select **one** combat owner after a Gauntlet comparison between Action RPG Template/Flexible Combat; do not stack duplicate damage/attribute/inventory/save systems. Pocket Creature Tamer is accelerator/reference for capture/taming but YOKAI's canonical data/evolution/fusion schema owns behavior. Element Reaction supplies/adapts elemental interactions. Boss AI/animations accelerate encounters. Multiplayer modules are evaluated against canonical authoritative-network contract.

## AXIOM implementation
AXIOM modules must satisfy the same stable contracts and golden gameplay tests. Migration tools should convert canonical game data, not Unreal implementation internals.

## XYRA
`CANON → REQUIREMENT → PLAN → IMPLEMENT → PLAYTEST → AUTOMATED TEST → PERFORMANCE → ADVERSARIAL REVIEW → FIX → EVIDENCE → PROMOTE`.

Gauntlet includes combat frame/latency tests, save corruption/recovery, creature data migrations, fusion invariants, multiplayer desync/host loss, boss exploits, progression economy, accessibility and performance budgets.

## Delivery
Foundation → movement/combat → creature data/capture → Canvas → boss/vertical slice → progression/content tools → multiplayer → campaign/content scale → optimization/certification → AXIOM parity track.

## Governance
Ø current instruction > this canon/build contract > approved design/system specs > ADRs > tickets. Material game-design changes escalate; AI agents cannot simplify signature systems to close tickets.