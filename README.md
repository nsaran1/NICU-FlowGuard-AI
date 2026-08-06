# NICU-FlowGuard-AI

# FlowGuard AI

## An Exception-Aware Command Center for Clinical Workflows

FlowGuard AI is a research prototype designed to detect missed, delayed, incomplete, and conflicting activities across clinical workflows.

Healthcare workflows depend on connected activities involving clinicians, departments, and technology systems. Breakdowns such as unacknowledged critical results, delayed patient follow-ups, missed clinical handoffs, and policy conflicts may remain invisible until they contribute to delayed care, safety incidents, clinician burnout, or compliance concerns.

FlowGuard AI monitors synthetic clinical workflow events, detects high-risk exceptions, explains why each exception matters, routes the alert to the appropriate clinical role, and records the resulting human-review decision in an audit trail.

## MVP Exception Types

The initial prototype focuses on four workflow exceptions:

1. Critical result not acknowledged
2. Follow-up task overdue
3. Clinical handoff not accepted
4. Workflow policy conflict

## Project Objective

The objective of this project is to determine whether a combination of transparent workflow rules and machine-learning models can identify and prioritize high-risk clinical workflow exceptions before they develop into serious operational or patient-safety incidents.

## Core Capabilities

FlowGuard AI will:

* Monitor synthetic clinical workflow events
* Detect predefined workflow exceptions
* Assign exception severity
* Generate an exception risk score
* Explain why an alert was generated
* Route alerts to the appropriate clinical role
* Support human acknowledgement, assignment, escalation, dismissal, and resolution
* Maintain an append-only audit history
* Display exceptions in a command-center dashboard
* Demonstrate a conceptual interaction with Dragon Copilot

## Human Oversight

FlowGuard AI does not diagnose patients, recommend treatment, prescribe medication, or independently modify clinical records. Every high-risk exception requires review and action by an authorized human user.

## Initial Models

The project will train and compare:

1. Logistic Regression
2. Decision Tree
3. Random Forest

The machine-learning component will prioritize detected workflow exceptions. It will not make independent clinical decisions.

## Data

The initial project uses entirely synthetic clinical workflow data. Synthetic data allows known workflow failures to be inserted safely and provides ground-truth labels for evaluating the system.

## Project Status

* [x] Phase 1 — Project definition
* [ ] Phase 2 — Data and feature design
* [ ] Phase 3 — Synthetic data generation
* [ ] Phase 4 — Exploratory data analysis
* [ ] Phase 5 — Data preprocessing
* [ ] Phase 6 — Exception-rule engine
* [ ] Phase 7 — Machine-learning models
* [ ] Phase 8 — Model evaluation
* [ ] Phase 9 — Risk scoring and explainability
* [ ] Phase 10 — Human review and routing
* [ ] Phase 11 — Audit trail
* [ ] Phase 12 — Dashboard
* [ ] Phase 13 — Dragon Copilot simulation
* [ ] Phase 14 — Governance and evaluation
* [ ] Phase 15 — Final report and presentation

## Disclaimer

FlowGuard AI is an academic and research prototype. It is not a medical device and is not intended for diagnosis, treatment, clinical decision-making, or production use. Prototype thresholds and workflow rules must not be interpreted as clinical standards.




