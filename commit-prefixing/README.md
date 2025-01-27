# Global Git Hooks Setup

This repository contains a template directory for global Git hooks. Follow these steps to configure Git to use these hooks globally:

## Setup Instructions
1.	Clone this repository to a location on your system, such as `~/.git-templates`:

```bash
git clone https://github.com/Adam-Reeves/useful-scripts.git
```

2. Copy the contents of the `hooks` directory to the `~/.git-templates/hooks` directory:

3. Set the template directory globally in your Git configuration:
```

```bash
git config --global init.templateDir ~/.git-templates
```

4. For repositories you already have, reinitialize them to copy the hooks into their `.git/hooks directory`:

```bash
cd /path/to/existing/repo
git init
```
