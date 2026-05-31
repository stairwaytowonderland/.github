# Contributing Guidelines

Thank you for contributing to the [**stairwaytowonderland**](https://github.com/stairwaytowonderland) organization! This guide will help you understand
our workflow and best practices when contributing to repositories.

## Workflow

### 1. Create a Branch

Always create a new branch for your work:

```bash
git checkout -b feature/descriptive-name
```

Branch naming conventions:

- `feature/` - New documentation or materials
- `update/` - Updates to existing content
- `fix/` - Corrections or bug fixes
- `template/` - New or updated templates

### 2. Make Your Changes

- Work in the appropriate directory ([folder1], [folder2], etc.)
- Commit frequently with clear messages
- Keep related changes together in a single commit

### 3. Commit Messages

Use clear, descriptive commit messages:

```none
Good examples:
- "Add client presentation template"
- "Update project status for Q4 initiatives"
- "Fix typos in onboarding documentation"

Avoid:
- "Updates"
- "Changes"
- "Fix stuff"
```

### 4. Push and Create Pull Request

```bash
git push origin your-branch-name
```

Then create a pull request on GitHub with:

- A clear title summarizing the changes
- A description explaining what and why
- Links to any related issues

### 5. Code Review

- At least one team member should review your PR
- Address feedback promptly
- Use comments to discuss suggestions
- Once approved, merge your PR

## Development Guidelines

### Code Style Guidelines

- Ensure your code is well-commented and self-documenting.
- The project enforces code formatting through its [pre-commits](.pre-commit-config.yaml) configuration.
  Do **NOT** turn off this feature and make sure your `pre-commit run` command works successfully
  (see [below](#pre-commit) for more details).

#### `pre-commit`

All projects should use [pre-commit](https://pre-commit.com/), a framework for managing and maintaining git hooks.
Pre-commit can be used to manage the hooks that run on every commit to automatically point out issues in code such as
missing semicolons, trailing whitespace, and debug statements. By using these hooks, you can ensure code quality and
prevent bad code from being uploaded.

To install `pre-commit`, you can use `pip`:

> [!TIP]
>
> **Creating a *virtual environment* is <ins>highly recommended</ins>**
>
> ```bash
> python3 -m venv path/to/venv # e.g. `python3 -m venv .venv`
> . path/to/venv/bin/activate  # e.g. `. .venv/bin/activate`
> ```
>
> **Typically, *'path/to/venv'* is *'.venv'* in the current directory: `python3 -m venv .venv`**
>
> Run `deactivate` to deactivate the *virtual environment*.

Please see the [official documentation](https://packaging.python.org/en/latest/tutorials/installing-packages/#optionally-create-a-virtual-environment)
for more information.

```bash
pip3 install pre-commit
```

After installation, you can set up your git hooks with this command at the root of this repository:

```bash
pre-commit install
```

This will add a pre-commit script to your `.git/hooks/` directory. This script will run whenever you run `git commit`.

For more details on how to configure and use pre-commit, please refer to the official documentation.

### Commit Message Guidelines

- Write clear, concise commit messages that follow the
  [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard.
- The allowed tags for this project are the following:

```json
[
  "build",
  "chore",
  "ci",
  "debug",
  "docs",
  "feat",
  "fix",
  "perf",
  "refactor",
  "remove",
  "style",
  "test"
]
```

## Content Guidelines

### Markdown Best Practices

- Use headers hierarchically (H1 → H2 → H3)
- Include a table of contents for longer documents
- Use code blocks with language specification: e.g. ```javascript
- Add alt text to images: `![Description](image.png)`
- Use relative links for internal references

### Naming Conventions

- Use lowercase with hyphens: `client-proposal-template.md`
- Be descriptive: `q4-2024-project-status.md` not `status.md`
- Include dates for time-sensitive materials: `2024-11-marketing-brief.md`

## What NOT to Commit

The [`.gitignore`](./.gitignore) file prevents unnecessary from being committed.

## Review Checklist

Before submitting a PR, ensure:

- [ ] Content is well-organized and in the correct folder
- [ ] File names follow naming conventions
- [ ] Markdown is properly formatted
- [ ] Links work correctly
- [ ] No final deliverable files are included
- [ ] Commit messages are clear and descriptive
- [ ] PR description explains the changes

## Getting Help

- **[Question Label]**: Open an issue with the [question] label
- **[Suggestion Label]**: Open an issue with the [enhancement] label
- **[Problem Label]**: Open an issue with the [bug] label

## License and Attribution

Projects should contain appropriate licenses and attributions.

For example, if using an [MIT License](https://choosealicense.com/licenses/mit/), create an appropriate `LICENSE` file, and place something like the following in your main `README.md` file.

> ```md
> ## License and Attribution
>
> This project is licensed under the [MIT License](./LICENSE). By contributing, you agree that your contributions will be licensed under the same terms.
> ```

See [Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) for more information.
