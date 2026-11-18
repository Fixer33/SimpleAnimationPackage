# Simple Animation - Open Questions

## Still open

### Scope and design
1. Which Animator features are planned (playing states, parameters, transitions, events, runtime controller changes)?
2. What does "simple" mean here: a thin wrapper over `Animator`, or a separate layer on top of it?
3. Is the plan to build it at all, or should the scaffold be removed?

### Package setup
4. Is the Editor assembly needed (e.g. custom inspectors)? It currently contains no scripts.
5. Should the namespace stay `SimpleAnimation` (taken from the asmdef root namespaces)?

### Release and documentation
6. Is the 1.0.0 version meant to represent an empty package, or should it stay until code exists?
7. Should samples and tests be added alongside the first code?

## Answered
- **Purpose:** working with Unity's Animator (planned, not implemented). Confirmed by the author.
- **Target frameworks / UI focus:** not applicable; the package is not about UI (confirmed by the author).
- **Library choice (standalone vs. an animation library):** not applicable under the Animator purpose; no dependency is declared.
- **package.json description wording:** updated to describe the planned Animator purpose (approved by the author).
- **README wording:** updated to describe the planned Animator purpose (approved by the author).
