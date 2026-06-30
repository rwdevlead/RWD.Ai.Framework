# Repository Maintenance

You are performing routine repository maintenance as a senior software architect and project maintainer.

Your objective is to keep the repository organized, accurate, and easy for both developers and AI agents to understand.

Before beginning:

1. Read `AGENTS.md`.
2. Restore the current project context from the project memory.
3. Review the repository structure.
4. Review the project plan.
5. Review the current documentation.

---

## Responsibilities

Perform a maintenance review of the repository.

Evaluate:

- Repository organization
- Folder structure
- Naming consistency
- Documentation quality
- Project memory accuracy
- Planning documents
- Prompt library
- AI policies
- Build configuration
- Test organization
- Technical debt

---

## Verify Repository Organization

Ensure the repository follows the established project standards.

Look for:

- Duplicate files
- Misplaced documents
- Empty directories
- Outdated files
- Obsolete prompts
- Stale templates
- Broken references
- Inconsistent naming
- Unused assets

Recommend improvements where appropriate.

---

## Verify Documentation

Review:

- README.md
- AGENTS.md
- User documentation
- Developer documentation
- Architecture documentation
- API documentation

Verify that documentation:

- Matches the current implementation
- Uses consistent terminology
- Contains no obsolete information
- References existing files
- Is well organized

Identify documentation that should be updated, archived, consolidated, or removed.

---

## Verify Project Memory

Review the project memory defined by `AGENTS.md`.

Verify that:

- Long-term memory reflects the current architecture.
- Session handoff reflects the current implementation status.
- Important architectural decisions have been preserved.
- Temporary information has not leaked into long-term memory.
- Long-term memory does not contain obsolete information.

Recommend updates where necessary.

---

## Review Planning Documents

Review all planning documents.

Identify:

- Completed plans that should be archived
- Plans that require updates
- Duplicate planning documents
- Obsolete implementation notes
- Completed milestones
- Outstanding work

Recommend archival or consolidation where appropriate.

---

## Review Prompts and Policies

Verify that prompts and AI policies:

- Are current
- Do not duplicate each other
- Reference valid files
- Reflect the current workflow
- Remain tool-agnostic where possible

Recommend simplifications where appropriate.

---

## Review Code Organization

Without changing functionality, identify opportunities to improve:

- Folder organization
- Namespace organization
- Project boundaries
- Layer separation
- Naming consistency
- Dependency organization

Do not perform large-scale refactoring unless requested.

---

## Technical Debt Review

Identify technical debt including:

- TODO items
- Deprecated code
- Dead code
- Duplicate logic
- Missing tests
- Missing documentation
- Build warnings
- Obsolete dependencies

Prioritize findings by impact.

---

## Archive Recommendations

Recommend items that should be archived, including:

- Completed planning documents
- Old design notes
- Historical implementation notes
- Superseded documentation
- Obsolete prompts

Do not delete historical information unless explicitly instructed.

Prefer archiving over deleting.

---

## Deliverables

Produce a maintenance report containing:

### Executive Summary

Overall repository health.

### Repository Health Score

Rate each area from 1–5:

- Organization
- Documentation
- Architecture
- Code Quality
- Project Memory
- Planning
- Maintainability

### Findings

List:

- Critical issues
- High-priority improvements
- Medium-priority improvements
- Low-priority improvements

### Recommended Actions

Provide an ordered list of the next maintenance tasks.

---

## Completion

Before finishing:

- Update project memory if repository organization changed.
- Record any new long-term architectural decisions.
- Update the session handoff with maintenance activities performed.
- Record any recommended follow-up work.

The goal of repository maintenance is continuous improvement, ensuring the repository remains clean, accurate, well-organized, and easy for both humans and AI agents to work with over the lifetime of the project.
