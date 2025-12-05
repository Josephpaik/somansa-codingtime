# CLAUDE.md - AI Assistant Guidelines

This file provides context and guidelines for AI assistants working with the somansa-codingtime codebase.

## Project Overview

**Repository:** somansa-codingtime
**Owner:** Josephpaik
**Status:** New project (initial setup)

This repository is in its early stages of development. As the project grows, this document will be updated to reflect the codebase structure, conventions, and workflows.

## Repository Structure

```
somansa-codingtime/
├── README.md          # Project documentation
├── CLAUDE.md          # AI assistant guidelines (this file)
└── .git/              # Git repository data
```

*Note: This structure will expand as development progresses.*

## Development Guidelines

### Git Workflow

1. **Branch Naming Convention:**
   - Feature branches: `feature/<description>`
   - Bug fixes: `fix/<description>`
   - AI-assisted branches: `claude/<session-identifier>`

2. **Commit Messages:**
   - Use clear, descriptive commit messages
   - Start with a verb in imperative mood (Add, Fix, Update, Remove)
   - Keep the first line under 72 characters
   - Add details in the body if needed

3. **Before Committing:**
   - Ensure code is properly formatted
   - Run any available tests
   - Review changes with `git diff`

### Code Style Conventions

*To be defined as the project develops. Common practices to follow:*

- Write clean, readable code with meaningful variable names
- Add comments for complex logic
- Follow the principle of single responsibility
- Keep functions/methods focused and concise

### Testing

*Testing framework and conventions will be documented here once established.*

## For AI Assistants

### When Working on This Repository

1. **Always read existing files** before making modifications
2. **Understand the context** of the project before suggesting changes
3. **Follow established patterns** in the codebase
4. **Prefer minimal changes** - don't over-engineer solutions
5. **Avoid adding unnecessary dependencies**

### Do Not

- Create files unless absolutely necessary
- Add features beyond what is requested
- Modify code without reading it first
- Push to branches without explicit permission
- Commit sensitive information (API keys, passwords, etc.)

### Best Practices

- Use existing utilities and helpers when available
- Maintain consistency with the existing codebase style
- Document any non-obvious code decisions
- Keep security in mind - validate inputs at system boundaries

## Quick Commands

```bash
# Check repository status
git status

# View recent commits
git log --oneline -10

# View changes before committing
git diff
```

## Updates

This document should be updated when:
- New major features or modules are added
- Development workflows change
- New conventions are established
- Dependencies or tooling are modified

---

*Last updated: 2025-12-05*
