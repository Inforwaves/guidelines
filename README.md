# Inforwaves GitHub Guidebook

Welcome to the Inforwaves GitHub Guidebook. This guide aims to standardize our GitHub practices to ensure smooth collaboration and maintainable code. Follow these guidelines to ensure consistency and efficiency in our workflow.

## Commit Guidelines

1. **Commit Messages**:
    - **Start with a Verb**: Each commit message should begin with a verb that clearly indicates the action taken. This makes it easier to understand the purpose of the commit at a glance.
      - Examples: `Fix`, `Add`, `Update`, `Remove`, `Refactor`.
    - **Describe the Change**: The message should provide a clear and concise description of what was done. Avoid vague descriptions and focus on what was changed and why.
      - Examples: `Fix bugs on the admin dashboard`, `Update user authentication flow`, `Add search functionality to the job portal`.
    - **Capitalization**: The first letter of the commit message should be uppercase.
    - **Length**: Aim to keep the message short but informative. If additional detail is needed, use the commit description field.

2. **Commit Frequency**:
    - **Milestones**: Commit your code whenever a task, functionality, or bug fix is completed. This helps in marking milestones and ensures that changes are documented incrementally.
    - **Atomic Commits**: Try to keep commits atomic, meaning each commit should represent a single logical change. This makes it easier to track changes and debug issues if they arise.
    - **Work in Progress (WIP) Commits**: If you're working on a longer task, consider using WIP commits to save your progress. Use the `--no-verify` flag if you need to bypass pre-commit hooks for intermediate states.

## Pull Request (PR) Guidelines

1. **When to Open a PR**:
    - **Significant Section Completed**: Open a PR when you've completed a significant section of work. This allows for easier review and integration into the main codebase.
    - **Scope**: Try to limit the PR to around 5-6 file changes and less than 1000 lines of code. This makes it easier for reviewers to provide thorough feedback without being overwhelmed.

2. **PR Titles and Descriptions**:
    - **Meaningful Titles**: The title should provide a clear summary of the changes. Avoid generic titles like "Fix issue" or "Update code."
      - Example: `Add pagination to job listings`, `Fix memory leak in user session management`.
    - **Detailed Descriptions**: In the PR description, list the work done as bullet points. Include any relevant context or background information to help reviewers understand the changes.
      - Example:
        ```markdown
        - Implemented pagination for job listings
        - Added unit tests for pagination functionality
        - Updated UI to support pagination controls
        ```

3. **Linking Issues**:
    - **Relevant Issues**: After opening a PR, link all relevant GitHub issues. This helps in tracking the progress and ensures that the work is connected to the broader project goals.
    - **Keywords**: Use keywords like `Closes #issue_number` or `Fixes #issue_number` to automatically close the issue when the PR is merged.

## Working with GitHub Issues

1. **Assignment**:
    - **Self-Assignment**: Before starting work on an issue, ensure you are assigned to it. If you are not assigned, request assignment from the project manager or team lead. This helps in avoiding duplicate efforts.
    - **Collaboration**: If an issue requires collaboration, ensure all team members involved are assigned and communicate regularly to coordinate efforts.

2. **Issue Status**:
    - **Working on It**: Change the status of the issue to `Working on` when you begin. This indicates to the team that the issue is in progress.
    - **Pending Review**: Once your work is ready for a PR, update the status to `Pending Review`. This signals that the issue is awaiting code review and testing.

## Additional Recommendations

- **Branch Naming**:
    - **Descriptive Names**: Use descriptive names for branches that indicate the work being done. This makes it easier to understand the purpose of the branch at a glance.
      - Example: `feature/add-login`, `bugfix/fix-header`, `hotfix/urgent-issue`.
    - **Consistency**: Follow a consistent naming convention across the team to avoid confusion.

- **Code Reviews**:
    - **Prompt Reviews**: Review PRs promptly to keep the workflow moving smoothly. Aim to provide feedback within 24 hours.
    - **Constructive Feedback**: Provide constructive feedback that helps improve the code quality. Be specific about what needs to be changed and why.
    - **Standards and Tests**: Ensure that the code follows coding standards and passes all tests before merging.

- **Documentation**:
    - **Update Documentation**: Update relevant documentation for any new features or changes. This includes README files, API documentation, and in-code comments.
    - **Clear Comments**: Ensure code comments are clear and useful. They should explain why certain decisions were made, especially for complex or non-obvious logic.

- **Testing**:
    - **Unit Tests**: Write unit tests for new features and bug fixes. This helps in catching issues early and ensures the code works as expected.
    - **Automated Tests**: Ensure all tests pass before merging a PR. Use continuous integration tools to automate the testing process and catch issues early.

By adhering to these guidelines, we can maintain high-quality code, streamline our development process, and facilitate better collaboration within the team. Happy coding!
