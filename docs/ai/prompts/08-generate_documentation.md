Generate Documentation

You are acting as a senior software architect responsible for maintaining accurate, high-quality project documentation.

Before making any documentation changes, review the entire repository as needed to understand the current implementation.

Follow the project’s README and Code Documentation Policy throughout this task.

Documentation is considered part of the implementation and must accurately reflect the current state of the project.

⸻

Review Objectives

Review the following before writing or updating documentation:

- Source code
- Project architecture
- AI project memory
- Existing documentation
- Architecture Decision Records (ADRs), if applicable

Use the implementation as the source of truth.

If documentation and implementation disagree, identify the discrepancy rather than guessing or inventing missing behavior.

⸻

Documentation Standards

Ensure all documentation:

- Reflects the current implementation.
- Is technically accurate.
- Is concise and well organized.
- Is written for the intended audience.
- Explains why and how, not merely what.
- Avoids duplication whenever practical.
- Includes examples where they improve clarity.
- Remains consistent across the repository.

Apply all standards defined in the project’s documentation policy.

⸻

Documentation Scope

Update only the documentation affected by the requested changes.

This may include, when applicable:

- README files
- Architecture documentation
- API documentation
- Deployment documentation
- Development documentation
- Configuration documentation
- Environment variable documentation
- Troubleshooting guides
- Contributor documentation
- ADRs
- Code comments
- XML documentation
- Makefile documentation

Do not modify unrelated documentation.

⸻

Code Documentation

Review public code for appropriate documentation.

Where applicable, ensure:

- Public classes are documented.
- Interfaces are documented.
- Public methods are documented.
- Complex logic includes meaningful comments.
- Business rules are explained.
- Performance considerations are documented.
- Security-sensitive behavior is documented.

Avoid comments that merely restate the code.

⸻

Documentation Validation

Before completing the task, verify that:

- Documentation matches the implementation.
- Examples are accurate.
- Commands are correct.
- Environment variables are documented.
- Public APIs are documented.
- Architecture documentation remains current.
- Makefile targets are documented.
- Internal references remain consistent.

⸻

AI Project Memory

If the documentation results in significant architectural, workflow, or operational changes:

- Update the long-term project context.
- Update the current session handoff.

Do not update AI project memory for minor wording, formatting, or editorial changes.

⸻

Deliverables

Produce only the documentation required by the requested task.

Do not invent functionality.

Do not speculate about future implementation.

Base all documentation on the current implementation.
