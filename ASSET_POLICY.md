# Asset Policy

`dark-bevy` provides engine code only. It does not distribute content from
*Thief Gold*, *Thief II*, or fan missions.

## Original game data

Users must provide their own legally obtained game installation.

The engine may read original game data at runtime, but it must not modify the
installation. Settings, caches, compatibility reports, crash reports, and saved
games must be written to a separate user-data directory.

## Repository and releases

Do not commit or distribute:

- missions or game-system databases;
- textures, models, animations, or fonts;
- music, speech, sound effects, or movies;
- maps, books, briefings, subtitles, or other extracted content;
- fan-mission content without explicit permission;
- converted, compressed, or otherwise transformed copies of such assets.

Public releases must contain only the engine, project-created resources, and
third-party resources whose licenses permit redistribution.

## Tests and fixtures

Committed tests must use:

- independently created synthetic data;
- project-created assets; or
- third-party material with a documented redistribution license.

Original game data and legally obtained fan missions may be used for private
local testing, but must remain outside the repository and build artifacts.

Tests may record hashes, structural measurements, and expected behavior as long
as they do not reproduce protected content.

## Reports and diagnostics

Compatibility and crash reports must avoid embedding game resources or file
contents. They may include format identifiers, object IDs, resource names,
versions, hashes, offsets, sizes, and error messages needed for diagnosis.

Reports should avoid exposing absolute installation paths or other unnecessary
personal information.

## Trademarks

Game titles and trademarks are used only to describe compatibility. The project
is unofficial and is not affiliated with or endorsed by the original
developers or publishers.