# YOKAI — Production Systems

## Canonical domains
Player, combat, Yokai, evolution/fusion, Divine Canvas, items/equipment, quests/narrative, world/regions, encounters/bosses, multiplayer, UI, audio, save/profile, analytics/debug.

## Data/save
Stable IDs for species/forms/moves/items/quests/regions. Versioned save schema with migration fixtures. Content validation rejects broken evolution/fusion links, missing assets and impossible encounters.

## AI
Behavior trees/state/utility systems for creatures/enemies; boss phase graphs; no cloud LLM dependency in combat. Offline AI may assist content authoring only.

## UI
Controller-first combat HUD, creature/team screens, evolution/fusion preview, Canvas interface, quest/map, accessibility and remapping.

## Audio
Creature identity, spatial ecology, combat telegraphs and Canvas feedback are first-class. SONARA/AUDIO FORGE can produce assets/tools but runtime accepts standard approved assets.

## Performance
Define platform budgets for frame, draw calls, animation, AI, streaming, memory and network. Creature crowds/partners use LOD/tick policies.

## Requirements
YOKAI-REQ-001 combat mastery; 002 creature lineage; 003 Canvas systemic verbs; 004 save migrations; 005 co-op authority; 006 boss phase correctness; 007 controller/accessibility; 008 Unreal/AXIOM golden parity fixtures.
