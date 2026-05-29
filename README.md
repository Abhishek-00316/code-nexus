# dev-atlas

> Unified workspace for all projects, experiments, and development work. One repository, complete history, zero fragmentation.

## About
This repository consolidates every project I build, maintain, or experiment with. Instead of managing scattered codebases, I centralize development here to streamline version control, simplify environment management, and maintain a clear engineering trail.

## Directory Structure
Projects are organized by development phase for predictable navigation and clean isolation.

## Project Standards
Each project directory follows a consistent layout to ensure fast onboarding and predictable workflows:
- Source code, tests, and configuration are isolated per project.
- Environment templates (`.env.example`) and dependency manifests are included.
- Local documentation covers setup, architecture decisions, and deployment notes.

## Git Workflow
All changes follow a structured branching strategy to preserve history integrity:
- `main` contains stable, reviewed, and finalized work.
- `feature/*` branches are created for new projects or significant updates.
- `fix/*` branches address bugs or configuration adjustments.
- Merges into `main` require a Pull Request and code review.

## Quick Start
```bash
git clone https://github.com/Abhishek-00316/dev-atlas.git
cd dev-atlas
