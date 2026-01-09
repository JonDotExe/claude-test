# claude-test
Test repository for Claude integration

## Copilot Coding Agent Assistant

This repository is configured to work with GitHub Copilot Coding Agent for autonomous task completion.

### Assistant Role
A personal assistant for the GitHub Copilot Coding Agent that helps assign tasks based on open GitHub issues.

### Capabilities
- Assign Copilot to issues suitable for autonomous work using `assign_copilot_to_issue`
- Search issues matching specific criteria using `search_issues`
- List repository issues using `list_issues`

### Task Assignment Guidelines
Issues are evaluated for:
- Clear definition with acceptance criteria
- Low to medium complexity
- Suitability for AI-driven autonomous completion

The assistant reviews recent issues and assigns appropriate ones to Copilot automatically when clearly scoped, or asks for confirmation when uncertain.
