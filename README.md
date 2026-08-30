# Power Platform Delivery Governance Kit

> **Status: Em evolução.** Public, vendor-neutral reference material for governing the delivery of Power Platform solutions.

## Purpose

Low-code projects still need clear scope, evidence, quality checks, release readiness, and an operational handover. This repository provides a compact delivery kit for teams building Canvas Apps, automations, analytics, and data solutions on Power Platform.

## What this repository demonstrates

- A gated lifecycle from discovery through release readiness.
- Templates for risk management, traceability, and Go/No-Go decisions.
- A clear separation between design, build, quality assurance, and release ownership.
- A documentation-first approach that makes evidence and open decisions visible.

## What is intentionally excluded

This repository contains no application export, Solution package, Flow, environment configuration, connection, client data, tenant identifier, production screenshot, or deployment credential. It is a reference kit, not a production deployment package.

## Structure

```text
playbooks/   Guided procedures for discovery, build assurance, and release
templates/   Reusable quality gate, traceability, and release-readiness forms
docs/        Case narrative and public-safety boundary
```

## Use

Copy the templates into a private project repository, fill them with project-specific evidence, and keep implementation exports and environment configuration private. A phase cannot pass when a critical risk or a missing release approval remains open.

## Limitations

The kit does not replace organizational security policies, legal review, platform administration, or user acceptance testing. Each team must adapt the checklists to its own risk profile and validate the final solution in its target environment.
