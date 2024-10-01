# 🛠️ Git Alias Setup Script

This script simplifies your Git workflow by setting up handy aliases for common Git commands. 🚀

## 📋 Description

Tired of typing long Git commands? This script sets up concise and meaningful aliases for frequently used Git operations like `checkout`, `branch`, `status`, `switch`, `log`, and `commit`. With these aliases, you can save time and boost productivity while working with Git.

### 📝 Git Aliases

Here's a list of the aliases created by the script:

- `git co` → Shorthand for `git checkout`
- `git br` → Shorthand for `git branch`
- `git st` → Shorthand for `git status`
- `git sw` → Shorthand for `git switch`
- `git loga` → Displays the Git log in a concise, one-line format
- `git cm` → Shorthand for `git commit -m`

## ⚙️ How to Use

You can add these aliases to your global Git configuration by running the following commands in your terminal or running the `git-aliases.sh` file:

```bash
git config --global alias.co checkout &&
git config --global alias.br branch &&
git config --global alias.st status &&
git config --global alias.sw switch &&
git config --global alias.loga 'log --oneline' &&
git config --global alias.cm 'commit -m'
