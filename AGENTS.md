# Repository Guidelines

## Project Structure & Module Organization

This repository is currently an empty starting point for a table tennis simulation. No source code, tests, assets, or build configuration have been added. Establish the layout with the first implementation and update this guide to reflect it.

Suggested directories, when needed:

- `src/`: simulation logic and application code.
- `tests/`: automated tests organized by the modules they exercise.
- `assets/`: models, textures, sounds, and other runtime resources.
- `docs/`: setup instructions and architecture notes.

Keep simulation rules and physics separate from rendering and input handling so they can be tested independently.

## Build, Test, and Development Commands

No build, test, or development commands are configured yet. When selecting a toolchain, document exact installation, local run, build, and test commands in `README.md`. Commit dependency manifests and lockfiles where supported. Do not document commands as working until they have been verified.

## Coding Style & Naming Conventions

Follow the chosen language’s standard conventions and use consistent indentation within each file. Add formatter and lint configuration when introducing the toolchain. Use descriptive names for simulation concepts, and name files consistently with neighboring modules. Replace unexplained numeric constants with named values that include units where relevant, such as `ball_radius_m`.

## Testing Guidelines

No testing framework or coverage threshold exists yet. Add tests alongside new behavior, particularly scoring, serves, collision handling, and simulation timing. Use descriptive test names that state the expected behavior. Prefer deterministic inputs and fixed random seeds for reproducible simulation tests.

## Commit & Pull Request Guidelines

There is no Git history from which to infer commit conventions. Use concise, imperative commit subjects, such as `Add ball collision handling`. Keep changes focused. Pull requests should describe the behavior changed, explain validation performed, link relevant issues, and include screenshots or recordings for visual changes.

## Configuration & Assets

Keep credentials and local environment files out of version control. Document required configuration and record the source and license of third-party assets.
