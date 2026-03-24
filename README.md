/reference/data#enrichment:company-ratings-by-employees UI Styles** - Glassmorphism, Claymorphism, Minimalism, Brutalism, Neumorphism, Bento Grid, Dark Mode, and more
- **95 Color Palettes** - Industry-specific palettes for SaaS, E-commerce, Healthcare, Fintech, Beauty, etc.
- **56 Font Pairings** - Curated typography combinations with Google Fonts imports
- **24 Chart Types** - Recommendations for dashboards and analytics
- **8 Tech Stacks** - React, Next.js, Vue, Svelte, SwiftUI, React Native, Flutter, HTML+Tailwind
- **98 UX Guidelines** - Best practices, anti-patterns, and accessibility rules

## Installation

### Using CLI (Recommended)

```bash
# Install CLI globally
npm install -g uipro-cli

# Go to your project
cd /path/to/your/project

# Install for your AI assistant
uipro init --ai claude      # Claude Code
uipro init --ai cursor      # Cursor
uipro init --ai windsurf    # Windsurf
uipro init --ai antigravity # Antigravity (.agent + .shared)
uipro init --ai copilot     # GitHub Copilot
uipro init --ai all         # All assistants
```

### Other CLI Commands

```bash
uipro versions              # List available versions
uipro update                # Update to latest version
uipro init --version v1.0.0 # Install specific version
```

### Manual Installation

Copy the appropriate folders to your project:

| AI Assistant   | Folders to Copy                                                     |
| -------------- | ------------------------------------------------------------------- |
| Claude Code    | `.claude/skills/ui-ux-pro-max/`                                     |
| Cursor         | `.cursor/commands/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`      |
| Windsurf       | `.windsurf/workflows/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`   |
| Antigravity    | `.agent/workflows/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`      |
| GitHub Copilot | `.github/prompts/ui-ux-pro-max.prompt.md` + `.shared/ui-ux-pro-max/`|

## Prerequisites

Python 3.x is required for the search script.

```bash
# Check if Python is installed
python3 --version

# macOS
brew install python3

# Ubuntu/Debian
sudo apt update && sudo apt install python3

# Windows
winget install Python.Python.3.12
```

## Usage

### Claude Code

The skill activates automatically when you request UI/UX work. Just chat naturally:

```
Build a landing page for my SaaS product
```

### Cursor / Windsurf / Antigravity

Use the slash command to invoke the skill:

```
/ui-ux-pro-max Build a landing page for my SaaS product
```

### GitHub Copilot

In VS Code with Copilot, type `/` in chat to see available prompts, then select `ui-ux-pro-max`:

```
/ui-ux-pro-max Build a landing page for my SaaS product
```

### Example Prompts

```
Build a landing page for my SaaS product

Create a dashboard for healthcare analytics

Design a portfolio website with dark mode

Make a mobile app UI for e-commerce
```

### How It Works

1. **You ask** - Request any UI/UX task (build, design, create, implement, review, fix, improve)
2. **Skill activates** - The AI automatically searches the design database for relevant styles, colors, typography, and guidelines
3. **Smart recommendations** - Based on your product type and requirements, it finds the best matching design system
4. **Code generation** - Implements the UI with proper colors, fonts, spacing, and best practices

### Supported Stacks

The skill provides stack-specific guidelines for:

- **HTML + Tailwind** (default)
- **React** / **Next.js**
- **Vue** / **Svelte**
- **SwiftUI** / **React Native** / **Flutter**

Just mention your preferred stack in the prompt, or let it default to HTML + Tailwind.

## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

- **Free for personal use** - Use, modify, and share for non-commercial purposes
- **Attribution required** - Credit "UI UX Pro Max" when sharing
- **No commercial use** - Cannot be used for commercial purposes without permission
