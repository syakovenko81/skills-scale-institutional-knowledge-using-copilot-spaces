# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged *(Developers, Product Manager validates)*
- Passing CI and security scans *(Developers, QA/Testers review)*
- Release notes drafted *(Technical Writer prepares, Product Manager reviews)*
- Rollback / mitigation plan documented *(Developers, Project Manager)*
- Smoke tests prepared *(QA/Tester)*
- User-facing documentation updated *(Technical Writer)*
- Design QA completed for UI changes *(UX/UI Designer validates)*

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) *(Project Manager)*
- [ ] Backup or snapshot (if applicable) *(Developer)*
- [ ] Deploy to staging and run smoke tests *(QA/Tester executes)*
- [ ] Deploy to production (automated pipeline preferred) *(Developer triggers)*
- [ ] Run post-deploy verifications *(QA/Tester, Developer)*
- [ ] Announce release to stakeholders and support *(Project Manager, Product Manager)*
- [ ] Update user documentation published *(Technical Writer)*
- [ ] Release notes published *(Technical Writer, Product Manager)*
- [ ] Monitor dashboards and alerts post-release *(Developer, QA/Tester)*

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call *(Developer, Project Manager)*
  - Rollback to last known-good release if necessary *(Developer)*
  - Triage root cause and capture action items *(Developer, QA/Tester)*
  - Conduct post-incident retrospective *(Scrum Master facilitates)*
  - Update incident documentation and lessons learned *(Technical Writer)*

## Release Notes Template
*(Technical Writer prepares, Product Manager reviews)*
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Documentation links:
