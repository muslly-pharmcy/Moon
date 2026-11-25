---
name: moon-agent-safety-qa
description: Audit Moon healthcare AI orchestration, UI, privacy and regression tests.
---

# moon-agent-safety-qa

README describes MUSLLY AI OS; package.json confirms React/Vite, Supabase, Sentry, Playwright and Vitest, but no mobile packaging scripts were verified. Inspect existing AGENTS and test environment first; run test, lint, build and test:e2e only with isolated fixtures. Check medical-answer citation/uncertainty, role boundaries, agent tool approvals, prompt injection resistance, RTL and reduced motion. Reuse Figma design rules only for actual UI changes. Do not duplicate YmPharma fixes without diffing architecture. No PHI in external tools.

## Execution contract
Read repo instructions and existing skills first. Prefer tools already installed; external plugins are candidates until connected and approved. Keep implementation and independent QA separate. Record exact commands, results, commit SHA, blockers and rollback. No production deploy, live writes or secret transfer. Source reference: https://github.com/openai/plugins. This is an original repo-specific skill, not a copy or proof of upstream plugin installation.
