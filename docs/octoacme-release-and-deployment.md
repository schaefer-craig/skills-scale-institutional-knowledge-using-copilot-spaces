# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (Developers, QA Lead)
- Passing CI and security scans (DevOps Engineer)
- Release notes drafted (Product Manager, Project Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared and executed (QA Lead)
- Design implementation validated (UX Designer)
- Success metrics and tracking confirmed (Data Analyst)
- Customer communication prepared (Customer Success Manager, for customer-facing releases)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) (Project Manager)
- [ ] Backup or snapshot (if applicable) (DevOps Engineer)
- [ ] Deploy to staging and run smoke tests (DevOps Engineer, QA Lead)
- [ ] Deploy to production (automated pipeline preferred) (DevOps Engineer)
- [ ] Run post-deploy verifications (QA Lead, DevOps Engineer)
- [ ] Validate metrics and dashboards (Data Analyst)
- [ ] Announce release to stakeholders and support (Project Manager, Customer Success Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer)
  - Assess impact and coordinate response (Project Manager, DevOps Engineer)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Monitor metrics for anomalies (Data Analyst, DevOps Engineer)
  - Communicate status to customers if needed (Customer Success Manager)
  - Triage root cause and capture action items (Project Manager, involved team members)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
