DOS – WORKFLOW PROTOCOL

Version: 1.0
Status: Initial Draft

1. Purpose

This document defines the standard collaboration and development workflow for DOS.

The objective is to ensure that architecture, engineering, testing and project decisions remain coordinated and traceable.

2. Project roles

Project Owner

The Project Owner:

- Defines strategic objectives.
- Approves priorities.
- Authorizes spending.
- Controls external account access.
- Approves major architectural decisions.
- Authorizes production deployment.

ChatGPT – Architecture Lead

ChatGPT:

- Prepares technical specifications.
- Defines engineering assignments.
- Evaluates architectural alternatives.
- Reviews Codex reports and implementation.
- Identifies inconsistencies and risks.
- Maintains alignment across sectors.

Codex – Engineering Agent

Codex:

- Inspects the repository.
- Executes authorized tasks.
- Creates and modifies technical files.
- Runs tests.
- Documents implementation decisions.
- Produces engineering reports.

3. Standard development cycle

Every significant development task follows this process:

Step 1 – Task definition

The Architecture Lead prepares an assignment containing:

- Task ID
- Objective
- Context
- Relevant documents
- Requirements
- Constraints
- Expected deliverables
- Acceptance criteria
- Explicit exclusions

Step 2 – Repository inspection

Codex must inspect the relevant repository files before acting.

It must identify missing information, inconsistencies and technical dependencies.

Step 3 – Execution

Codex performs only the work authorized by the assignment.

Unexpected architectural problems must be reported rather than silently resolved through major changes.

Step 4 – Engineering report

Codex provides:

- Summary of work
- Files created or modified
- Technical decisions
- Tests executed
- Actual test results
- Risks and limitations
- Open questions
- Recommendations

Step 5 – Independent review

The Architecture Lead reviews the output against:

- Original requirements
- Project architecture
- Security principles
- Data integrity
- Quality criteria
- Long-term maintainability

Step 6 – Decision gate

The Project Owner approves strategic decisions and any changes involving costs, external permissions or deployment.

Step 7 – Project update

Once accepted:

- Documentation is updated.
- Project state is updated.
- Decision log is updated.
- Next task is prepared.

4. Task management

Every assignment must have a unique identifier.

Initial task sequence:

- DOS-001: Independent Architecture Review.
- DOS-002: Architecture Reconciliation and Specification Update.
- DOS-003: DOSL Metamodel Definition.
- DOS-004: Schema Registry Design and Implementation.
- DOS-005: Registry Testing and Validation.
- DOS-006: Core Engine Design.
- DOS-007: Core Engine Implementation.

Tasks must not be considered authorized merely because they appear in this list.

Each implementation task requires explicit authorization.

5. Git workflow

The repository is the shared source of truth for project documentation and code.

Recommended practices:

- Keep the main branch stable.
- Use dedicated branches for significant tasks.
- Keep changes focused and reviewable.
- Provide meaningful commit messages.
- Never commit secrets.
- Review changes before merging.
- Preserve previous versions and project history.

For substantial implementation, Codex should propose changes through a pull request whenever practical.

6. Documentation rules

Important architectural decisions must be documented.

Technical reports should be stored in the appropriate project directories.

The following files must remain current:

- PROJECT_STATE.md
- DECISION_LOG.md
- OPEN_DECISIONS.md
- ARCHITECTURE_DECISIONS.md

Do not overwrite the original Master Build Specification during an independent review.

7. Quality gates

A task is not complete merely because files have been created.

Completion requires:

- Deliverables present.
- Requirements checked.
- Tests executed where applicable.
- Results documented.
- Known limitations disclosed.
- Review completed.
- Required approval obtained.

8. Cost and security controls

No agent may independently authorize:

- Paid subscriptions.
- Cloud infrastructure charges.
- Advertising expenses.
- External integrations.
- Production deployment.
- Irreversible account or data operations.

All such actions require Project Owner approval.

9. Handling disagreements

If Codex identifies a weakness in an existing specification:

1. Explain the problem.
2. Identify its consequences.
3. Propose alternatives.
4. Compare advantages and disadvantages.
5. Recommend one approach.
6. Wait for the appropriate decision before implementing major changes.

Technical disagreement is encouraged when supported by evidence.

10. Current workflow stage

The project is currently preparing DOS-001.

The next authorized activity is independent architecture review.

Substantial software implementation remains on hold until the review has been assessed and the architecture approved.
