# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Current State

This repository (`enpitproemb2`) is in an early, pre-development state. As of this writing it
contains only a placeholder `README.md` with no source code, build system, tests, dependency
manifests, or CI configuration. There is no application architecture to document yet.

When real code is introduced, this file should be expanded to cover:
- Build, lint, test, and run commands (including how to run a single test)
- High-level architecture that spans multiple files
- Project-specific conventions

Keep this section honest: do not document tooling or structure that does not actually exist in
the repo. Update the sections below as the project takes shape.

## Repository Conventions

- Default branch: `main`.
- Development happens on feature branches that are merged into `main` via pull requests
  (see existing history, e.g. branches named `feature_sample`). Do not commit directly to `main`.
- The project name `enpitproemb` suggests an enPiT (Japanese university PBL/PBL-style project)
  context; documentation and commit messages may be in Japanese or English.
