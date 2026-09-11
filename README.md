# YOKAI — Dual-Engine Game Blueprint

> Soulslike action RPG × creature collection/evolution/fusion × mythic ink/canvas world.
> Canonical game specification supports an Unreal-first production build and an AXIOM-XIII native build.

## Pillars
- demanding, readable action combat;
- collectible Yokai with capture/bond/evolution/fusion;
- Divine Canvas: world/combat traversal and reality-altering artistic power;
- mythic exploration, bosses, secrets and meaningful builds;
- co-op/PvP designed around the core game rather than bolted on;
- strong authored narrative and world identity.

## Unreal-first foundation
Default base: **Narrative Pro 2 + Ultra Game Template 1.3**, reconciled so each subsystem has one owner. Recommended Fab layers from Ø's library: Action RPG Template / Flexible Combat System Framework (evaluate and select combat owner), Pocket Creature Tamer Adventure for creature-system acceleration, Element Reaction System, Boss AI Toolkit, Boss Animations Pack, BlackMoon/Sci-Fi Myth boss content as reference/content where stylistically suitable, Action RPG Multiplayer Combat for networking reference, VisAI/Squad AI where useful, HKH Attribute System only if superior to the selected base attribute implementation, Building System only for explicitly designed construction features.

## AXIOM build
Reimplement the canonical YOKAI contracts using AXIOM runtime/rendering/gameplay/AI/networking/project format and PYRAMID services. Unreal is behavioral/reference implementation, not disposable canon.

## Version gates
**V1:** vertical slice: one region, combat, Divine Canvas core, capture/bond, evolution/fusion prototype, 8–12 Yokai, boss, save/UI, one co-op test path.
**V2:** production game: multiple regions, deep roster/ecosystem, advanced bosses, progression/crafting, co-op, PvP ruleset, narrative campaign, accessibility/performance/content pipeline.
**V3:** franchise/end-state: expanded world/endgame, competitive/social systems, live content tooling where desired, AXIOM-native parity/superiority and PYRAMID integration.

See `MASTER_BLUEPRINT.md` for systems, XYRA, Fab reconciliation and delivery architecture.