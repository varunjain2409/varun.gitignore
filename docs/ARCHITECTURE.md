# Architecture - varun.gitignore

## Overview

Reusable .gitignore templates for common stacks - Java, Python, Node, Java/NetBeans and general projects.

## Layers

| Layer          | Responsibility                                |
|----------------|-----------------------------------------------|
| Presentation   | UI / CLI entry points                         |
| Application    | Orchestration and use-case handling            |
| Domain         | Core logic and data models                     |
| Infrastructure | External services, storage and configuration   |

## Design Principles

1. Keep domain logic free of framework dependencies.
2. Externalise configuration - never hard-code secrets.
3. Test every layer independently.

## Development Workflow

1. Branch from the default branch.
2. Implement and test the change locally.
3. Open a pull request describing the change.

## License

MIT - see [LICENSE](../LICENSE).