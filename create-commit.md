# Commit Message Generation Guidelines

When generating commit messages:

## 1. Organize changes by category
- Group related changes under descriptive category headings
- Use semantic categories (e.g., "Feature", "Bug Fix", "Refactor", "Documentation")

## 2. Include all changes
- Address every modified file or component
- Don't omit small changes

## 3. Use bullet point structure
- Main categories as section headers
- Individual changes as bullet points under appropriate category
- Sub-bullets for more detailed explanations when necessary

## 4. For each bullet point:
- Start with a clear action verb (Added, Fixed, Updated, Removed, etc.)
- Be specific about what changed and where
- Include issue/ticket references when applicable

## 5. Format consistently
- Use imperative mood for all descriptions
- Keep bullet points concise (1-2 lines)
- Use present tense

## Example format:
```
Feature: Add user authentication
- Implement JWT token generation and validation
- Create login and registration endpoints
- Add password hashing utilities

Bug Fix: Address form submission issues
- Fix validation error on empty email field
- Correct form reset functionality after submission
- Resolve CORS issue with API endpoints

Refactor: Improve code organization
- Extract form logic into separate hooks
- Consolidate duplicate utility functions
- Move constants to dedicated configuration file
```
