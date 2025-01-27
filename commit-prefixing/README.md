# Global Git Hooks Setup

This repository contains a template directory for global Git hooks. Follow these steps to configure Git to use these hooks globally:

## Setup Instructions
1.	Clone this repository to a location on your system, such as `~/.git-templates`:

```bash
git clone <repository-url> ~/.git-templates
```

2. Set the template directory globally in your Git configuration:

```bash
git config --global init.templateDir ~/.git-templates
```

3. For repositories you already have, reinitialize them to copy the hooks into their `.git/hooks directory`:

```bash
cd /path/to/existing/repo
git init
```
