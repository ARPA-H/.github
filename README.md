# ARPA-H `.github` Repository

This repository contains organization-wide GitHub configuration for the [ARPA-H](https://arpa-h.gov) GitHub organization.

## What This Repo Does

GitHub treats a repository named `.github` in an organization as a special configuration repository. Files placed here apply defaults across **all repositories** in the organization unless overridden at the individual repository level.

## Contents

| Path | Purpose |
|---|---|
| `.github/CODEOWNERS` | Default code owners for this repository. |
| `.github/rulesets/` | Organization-wide branch and tag ruleset definitions. |
| `profile/README.md` | The public-facing organization profile displayed on the [ARPA-H GitHub org page](https://github.com/ARPA-H). |

## Why It Exists

Centralizing configuration here keeps security policies, review requirements, and public-facing content consistent and auditable in one place rather than scattered across individual repositories.
