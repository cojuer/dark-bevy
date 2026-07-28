# Compatibility

`dark-bevy` aims to run legally obtained content made for the original Dark
Engine games. Compatibility is measured per mission and feature.

The project is currently at an initial prototype stage. No original mission is
supported yet.

## Compatibility levels

| Level | Name | Meaning |
| --- | --- | --- |
| L0 | Recognized | The content is identified and can be inspected. |
| L1 | Rendered | World geometry, objects, textures, and lighting are displayed. |
| L2 | Interactive | The mission can be navigated and its essential objects can be used. |
| L3 | Completable | Objectives, difficulty rules, scripts, AI, and progression allow the mission to be completed. |
| L4 | Campaign-tested | The mission has been tested as part of its campaign, including transitions and save/load behavior. |

A mission receives the highest level for which every requirement is satisfied.

## Target order

Compatibility work proceeds in this order:

1. *Thief II* training mission.
2. *Thief II: Running Interference*.
3. The complete *Thief II* campaign.
4. The complete *Thief Gold* campaign.
5. Fan missions.

## Supported behavior

The intended result is recognizable movement, rendering, interaction, stealth,
AI behavior, objectives, and mission progression.

Exact reproduction of timing bugs, rendering artifacts, exploits, crashes, and
other accidental behavior is not required. Compatibility fixes should normally
improve reusable engine systems rather than depend on mission-specific checks.

## Explicit exclusions

The following are outside the current compatibility target:

- original Dark Engine save files;
- execution of arbitrary native `.osm` script modules;
- multiplayer;
- an integrated mission editor;
- bug-for-bug or frame-perfect emulation;
- automatic downloading of original games or fan missions.

Unknown native scripts and unsupported formats must produce visible diagnostics
instead of being treated as working.

## Mission status

Mission-level results will eventually record:

| Mission | Load | Render | Interaction | Objectives | Save/load | Level | Known deviations |
| --- | --- | --- | --- | --- | --- | --- | --- |

No missions have been evaluated yet.