# Simple Animation (com.fixer33.simple-animation) - Package Description

Version 1.0.0 (package.json), display name "Simple animation", Unity 6000.0 or newer, author Fixer33, MIT license.

## Purpose (planned, not implemented)

Planned (confirmed by the author): working with Unity's Animator. No specific features or API have been defined yet, and none of it is implemented.

## Who uses it

Intended for the author's own Unity projects (personal and work) (assumed, in line with the author's other `com.fixer33.*` packages). Installed from the Git URL given in the README (`https://github.com/Fixer33/SimpleAnimationPackage.git`).

## Current state

**Empty scaffold. There is no C# code**, no types, no samples, no tests.

What exists:
- `package.json` (version 1.0.0).
- `Runtime/com.fixer33.simple-animation.asmdef` (name `com.fixer33.simple-animation`, root namespace `SimpleAnimation`, auto-referenced, no references, no define constraints).
- `Editor/com.fixer33.simple-animation.Editor.asmdef` (name `com.fixer33.simple-animation.Editor`, root namespace `SimpleAnimation.Editor`, Editor platform only, references the Runtime asmdef by GUID).
- `README.md`, `CHANGELOG.md` (only "1.0.0 - 2025-06-05, created first version of package"), `LICENSE.md`.

Because both assemblies contain no scripts, Unity may warn that the asmdefs have no scripts; the package currently does nothing.

## Dependencies

- `package.json`: none declared (no `dependencies` section).
- Runtime asmdef: no references, no version defines.
- Editor asmdef: references only the package's own Runtime assembly.
- The Animator belongs to Unity's built-in animation module; no extra package dependency is declared (assumed none is needed).

## What is missing

- Any runtime code (the Animator-related API and components).
- Editor code, if any is planned.
- Samples and tests (no test asmdefs).
- Usage documentation (no usage guide exists because there is no API yet).
- A defined feature scope.
- Changelog entries beyond the initial one.
