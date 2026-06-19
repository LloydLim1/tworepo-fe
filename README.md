# tworepo-frontend

This repository was created and configured by FlowCI Studio.

## Branch strategy

| Branch  | Purpose |
|---------|---------|
| main    | Stable baseline — protected |
| uat     | Pre-production gate — protected |
| test    | Integration target — protected |
| develop | Staging/integration branch — protected, no CI pipeline |

## CI/CD

Workflow files live in `.github/workflows/`. The CI pipeline runs on `test`, `uat`, and `main` only; `develop` is a protected staging branch with no pipeline. Push to `test` to trigger your first run.

## Getting started

Clone this repository, install dependencies, and push your code to a feature branch targeting `test` to activate the CI pipeline.