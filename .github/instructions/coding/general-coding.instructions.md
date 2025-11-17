---
applyTo: '**'
---

# Project general coding standards

## Naming Conventions

- Use PascalCase for component names, interfaces, and type aliases
- Use camelCase for variables, functions, and methods
- Prefix private class members with underscore (\_)
- Use ALL_CAPS for constants

## Error Handling

- Use try/catch blocks for async operations
- Always log errors with contextual information

## Coding Guidelines

### Indentation

We use spaces, not tabs.

### Naming Conventions

- Use PascalCase for `type` names
- Use PascalCase for `enum` values
- Use camelCase for `function` and `method` names
- Use camelCase for `property` names and `local variables`
- Use whole words in names when possible

### Types

- Do not export `types` or `functions` unless you need to share it across multiple components
- Do not introduce new `types` or `values` to the global namespace
-

### Comments

- Use JSDoc style comments for `functions`, `interfaces`, `enums`, and `classes`

[//]: # '### Strings'
[//]: #
[//]: # '- Use "double quotes" for strings shown to the user that need to be externalized (localized)'
[//]: # "- Use 'single quotes' otherwise"
[//]: # '- All strings visible to the user need to be externalized using the `vs/nls` module'
[//]: # '- Externalized strings must not use string concatenation. Use placeholders instead (`{0}`)'

### Code Quality

- Never duplicate imports. Always reuse existing imports if they are present
- Prefer `async` and `await` over `Promise` and `then` calls
- Look for existing test patterns before creating new structures
- Use `describe` and `test` consistently with existing patterns
- If you create any temporary new files, scripts, or helper files for iteration, clean up these files by removing them at the end of the task
