# AGENT.md

Welcome, AI Agent. This file is your primary guide for working on the **Conference Attendance Optimizer**.

## Project Mission
The goal is to optimize employee attendance at conferences based on company goals (learning vs. networking), employee availability, budget, and expertise.

## Core Responsibilities
- **PRP Framework Execution**: Follow the Proactive Review & Planning lifecycle (PRD -> Plan -> Implementation -> Report).
- **Search & Filter**: Find relevant conferences.
- **Employee Matching**: Match employees to events based on skills and budget.
- **Availability Management**: Integrate with calendars and handle manual blocks.
- **Logistics Estimation**: Estimate travel, food, and accommodation costs.
- **Booking & Scheduling**: Manage the acceptance/rejection flow and update calendars/budgets.

## PRP Framework (Product Requirement Prompts)
This project uses the PRP framework for agentic engineering.
- **Artifacts**: All PRP artifacts are in `.ai/PRPs/`.
  - `prds/`: Detailed requirements documents.
  - `plans/`: Step-by-step implementation plans.
  - `reports/`: Outcome reports for completed tasks.
- **Templates**: Use templates in `.ai/templates/` for new documents.
- **Rules**: Never start a medium or large task without a PRD and an approved Plan.


## AI Guidelines for Context & History
To ensure continuity and deep understanding, follow these rules:
1. **Directory**: All AI-specific context and history must be stored in the `.ai/` directory.
2. **Context**: Check `.ai/context/` for:
   - `architecture.md`: System design and tech stack.
   - `decisions.md`: Record of key technical decisions.
   - `state.md`: Current progress of features.
3. **History**: Check `.ai/history/` for past session summaries to understand "how" and "why" things were done.
4. **Primacy of README**: The root `README.md` is the source of truth for features; `AGENT.md` is the source of truth for *how* you should work.

## Development Workflow
- **Git Flow**: This project follows Git Flow.
  - `main`: Production-ready code.
  - `develop`: Main development branch.
  - `feature/*`: For new features.
  - `hotfix/*`: For critical patches.
- **Commits**: Make frequent, descriptive commits. Do not push to remote unless instructed; work locally first.

## Getting Started
1. Read `README.md`.
2. Explore `.ai/context/` to see where we are.
3. Check `.ai/history/` for the latest updates.
4. Always update `.ai/history/` when finishing a task.
