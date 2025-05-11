# Quickfolio Project Management

This repository serves as the project management hub for [Quickfolio](https://github.com/socrabytes/quickfolio) development.

## Project Organization

### Board Columns

- **Backlog**: New issues that need to be prioritized
- **Todo**: Ready for development, fully specified
- **In Progress**: Currently being worked on
- **Bugs**: Issues that need fixing
- **Done**: Completed work

### Issue Management

We use GitHub issues to track all tasks. When creating issues:

1. Use appropriate templates
2. Add to the project board
3. Apply relevant labels
4. Link to related issues/PRs

### Branch Management

- Create branches using: `[type]/[issue-number]-[description]`
  - Example: `feat/1-custom-domain-wizard`
- Types:
  - `feat/` - New features
  - `fix/` - Bug fixes
  - `refactor/` - Code improvements
  - `docs/` - Documentation
  - `test/` - Testing improvements

### Pull Request Process

1. Create PR with detailed description
2. Link to related issue
3. Request reviews if needed
4. Merge with simple merge commit
5. Delete branch after merge

### Commit Messages

We follow the [Gitmoji](https://gitmoji.dev/) convention:

```
✨ (scope): Brief description

Longer description if needed.
Paths: file1.py, file2.js
```

## Active Milestones

### Phase 1: Public Alpha

- ✅ GitHub OAuth integration
- ✅ CLI-less onboarding UI 
- 🔄 Custom domain wizard (next focus)
- 🔄 Lite hosting plan option

### Code Quality Initiatives

- 🔄 Pydantic v2 updates
- 🔄 Error handling improvements
- 🔄 Testing framework

## Getting Started

To contribute:

1. Find or create an issue
2. Add it to the project board
3. Create a branch following naming conventions
4. Submit a PR when ready

## Links

- [Main Repository](https://github.com/socrabytes/quickfolio)
- [Documentation](https://github.com/socrabytes/quickfolio/tree/main/docs)