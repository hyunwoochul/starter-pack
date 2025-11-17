# Git Commit Instructions

Please follow these instructions when generating commit messages:

## General Guidelines

- Ensure the commit message is written in English.
- Separate the subject from the body with a blank line.
- Separate the body from the footer with a blank line.

## Subject

- Use the present tense ("Add feature" not "Added feature").
- Use the imperative mood ("Fix bug" not "Fixes bug").
- Subject line should be concise and descriptive, ideally under 50 characters.
- Do not end with a period.
- Capitalize the first letter.
- Avoid using "I" or "we".
- Keep it concise, ideally under 50 characters.
- Avoid using special characters or emojis in the subject line.
- Start the subject line with a type:
    - `feat`: A new feature
    - `fix`: A bug fix
    - `build`: Changes that affect the build system or external dependencies
    - `ci`: Changes to our CI configuration files and scripts
    - `docs`: Documentation only changes
    - `style`: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
    - `refactor`: A code change that neither fixes a bug nor adds a feature
    - `test`: Adding missing or correcting existing tests
    - `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation
    - `perf`: A code change that improves performance
    - `prelease`: A version bump or release-related changes
    - `release`: A version bump or release-related changes
- If the commit addresses an pull request, reference it in the end of the subject line (e.g., "feat: add new feature for user login (PR #123)")
- If the commit addresses an issue, reference it in the end of the subject line (e.g., "fix: resolve issue with user login (Issue #456)")

## Body

- Use the first line for a brief summary.
- Use subsequent lines for detailed explanations.
- Use bullet points for lists to improve readability.
- Keep the body under 72 characters per line to ensure readability in various interfaces.
- The body should provide a detailed description of the change, explaining what and why, not how.

## Footer
