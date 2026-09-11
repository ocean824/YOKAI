# YOKAI — AXIOM Native Build

AXIOM implementation consumes the same canonical game rules/canon as Unreal and must match/improve reference behavior rather than reinterpret the game.

Required AXIOM capabilities: third-person character controller/camera, animation/state/motion system, collision/physics, ability/combat framework, data-driven creature runtime, AI behavior, navigation, world streaming, particles/VFX, audio, UI, save/versioning, networking/co-op/PvP, tooling and profiler.

YOKAI-specific AXIOM modules: Yokai registry/evolution/fusion, Divine Canvas world-interaction graph, elemental reactions, boss encounter framework and creature/network authority.

Migration approach: extract engine-neutral schemas and golden behavioral tests from Unreal; implement AXIOM adapters; compare combat timings, creature outcomes, save fixtures and encounter state; do not attempt binary Unreal asset/code compatibility where licensing/technical constraints make it inappropriate—use approved source assets/pipelines.

PYRAMID integration: launcher identity, achievements/social/store/wallet features remain optional platform services and cannot be required for offline core gameplay unless explicitly designed.
