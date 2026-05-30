# Contributing to UI UX Pro Max

## Code of Conduct

We are committed to providing a welcoming and inclusive environment for all contributors.

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Expected Behavior

- Use welcoming and inclusive language
- Be respectful of differing opinions, viewpoints, and experiences
- Accept constructive criticism gracefully
- Focus on what is best for the community
- Show empathy towards other community members

### Unacceptable Behavior

- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information, such as a physical or electronic address, without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

## How to Contribute

### Ways to Contribute

1. **Report Bugs**: Find and report issues
2. **Suggest Features**: Propose new styles, palettes, or guidelines
3. **Improve Documentation**: Help clarify and expand docs
4. **Write Code**: Fix bugs or implement features
5. **Create Content**: Design styles, color palettes, typography
6. **Community Support**: Answer questions and help others

### Getting Started

#### Prerequisites

- Node.js 18+ or Bun
- Python 3.x
- Git
- GitHub account

#### Development Setup

```bash
# Fork the repository
git clone https://github.com/YOUR_USERNAME/ui-ux-pro-max-nextgenaillc.git
cd ui-ux-pro-max-nextgenaillc

# Install dependencies
bun install
# or
npm install

# Create a feature branch
git checkout -b feature/your-feature-name

# Make your changes
# ...

# Run tests
bun run test

# Commit your changes
git commit -m "feat: description of your changes"

# Push to your fork
git push origin feature/your-feature-name

# Create a Pull Request
```

## Submission Guidelines

### Git Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) standard:

```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, missing semicolons, etc.)
- `refactor`: Code refactoring without feature changes
- `perf`: Performance improvements
- `test`: Adding or updating tests
- `ci`: CI/CD configuration changes
- `chore`: Build process, dependencies, etc.

**Examples:**
```
feat(colors): add fintech color palette
fix(cli): resolve installation error on Windows
docs(readme): update installation instructions
style(search): format Python search script
```

### Pull Request Process

1. **Create a descriptive PR title** following commit message conventions
2. **Link related issues** (e.g., "Closes #123")
3. **Describe changes** clearly in PR description
4. **Include screenshots** for UI/design changes
5. **Update documentation** if applicable
6. **Add tests** for new features
7. **Ensure CI passes** (all checks green)
8. **Request review** from maintainers

### PR Template

```markdown
## Description
Briefly describe the changes.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Related Issues
Closes #(issue number)

## Changes Made
- List specific changes
- Include file modifications
- Describe implementation details

## Testing
Describe how you tested the changes.

## Checklist
- [ ] Code follows style guidelines
- [ ] Documentation updated
- [ ] Tests added/updated
- [ ] No breaking changes
- [ ] License/attribution preserved
```

## Contribution Types

### Bug Reports

When reporting a bug, include:

1. **Title**: Clear, specific bug description
2. **Environment**: OS, Node version, relevant tools
3. **Steps to reproduce**: Exact steps to recreate
4. **Expected behavior**: What should happen
5. **Actual behavior**: What actually happened
6. **Screenshots/logs**: Visual or log evidence
7. **Possible solution**: Ideas for fixing (optional)

**Example Issue:**
```markdown
## Bug: CLI installation fails on Windows

### Environment
- Windows 11 Pro
- Node 18.16.0
- npm 9.6.4

### Steps to Reproduce
1. Run `npm install -g uipro-cli`
2. Run `uipro init --ai copilot`
3. Error occurs

### Error Output
```
Error: EACCES: permission denied...
```

### Expected
CLI should install without permission errors
```

### Feature Requests

When suggesting features, include:

1. **Title**: Clear feature name
2. **Problem**: What problem does it solve?
3. **Solution**: How should it work?
4. **Use case**: Real-world example
5. **Alternatives**: Other possible approaches

**Example Feature Request:**
```markdown
## Feature: Glassmorphism palette variations

### Problem
Glassmorphism is trending, but limited color options.

### Solution
Create 10 glassmorphism palettes for different industries:
- Tech (blues, purples)
- Finance (blacks, golds)
- Healthcare (greens, whites)

### Use Case
Designers need quick, industry-appropriate glassmorphic colors.
```

### Design Contributions

#### Adding UI Styles

1. Create `styles/<style-name>.md`
2. Include:
   - Style overview
   - Key characteristics
   - Code implementation
   - Component examples
   - Use case recommendations
   - Accessibility notes

**Template:**
```markdown
# [Style Name]

## Overview
[Description of the style]

## Key Characteristics
- Feature 1
- Feature 2
- Feature 3

## Implementation
[Code examples]

## When to Use
- Use case 1
- Use case 2

## Best Practices
- Practice 1
- Practice 2

## Accessibility
[Accessibility considerations]
```

#### Adding Color Palettes

1. Create `palettes/<palette-name>.json`
2. Include hex codes, RGB, HSL values
3. Document industry/use case
4. Provide preview

**Format:**
```json
{
  "name": "Palette Name",
  "industry": "SaaS",
  "colors": {
    "primary": "#1E40AF",
    "secondary": "#7C3AED",
    "accent": "#F59E0B",
    "background": "#FFFFFF",
    "text": "#1F2937"
  },
  "description": "Professional SaaS palette"
}
```

#### Adding Font Pairings

1. Create `fonts/<pairing-name>.md`
2. Include:
   - Font names & Google Fonts links
   - Preview
   - Best use cases
   - CSS/implementation

## Community Roles

### Contributors
- Submit code, designs, documentation
- Participate in discussions
- Report issues

### Reviewers
- Review pull requests
- Provide constructive feedback
- Help maintain code quality

### Maintainers
- Merge pull requests
- Manage releases
- Handle security issues
- Set project direction

### Community Ambassadors
- Share on social media
- Write blog posts
- Host workshops
- Moderate community spaces

**Interested?** Email: community@nextgenaillc.dev

## Recognition

We recognize and appreciate all contributions:

- **Contributors**: Listed in README and CONTRIBUTORS.md
- **Featured**: Highlighted in release notes
- **Ambassador Program**: Special perks for active community members
- **Rewards**: Eligible for revenue sharing on features

## Legal

### License

All contributions are licensed under the MIT License. By contributing, you agree that your contributions will be licensed under its terms.

### Copyright

Contributors retain copyright to their original work. By contributing, you grant NextGenAILLC a perpetual, worldwide, non-exclusive, royalty-free license to use, modify, and distribute your contributions.

### Attribution

Your name will be credited in:
- CONTRIBUTORS.md
- GitHub contributors page
- Release notes (for major contributions)
- Project documentation

## Support

Need help?

- **GitHub Issues**: Report bugs and request features
- **Discussions**: Ask questions and discuss ideas
- **Discord**: Real-time community chat
- **Email**: contributors@nextgenaillc.dev

## Recognition Examples

### Contributor Levels

**Bronze** (1-4 contributions)
- Listed in CONTRIBUTORS.md
- GitHub contributor badge
- Community Discord role

**Silver** (5-19 contributions)
- All Bronze benefits
- Featured in newsletter
- Priority support
- 10% discount on premium

**Gold** (20+ contributions)
- All Silver benefits
- Co-author on features
- Revenue sharing eligible
- Advisory board consideration

## Questions?

Please open a discussion or email: contributors@nextgenaillc.dev

Thank you for contributing! 🚀
