# Hi! 👋

![GitHub Profile Views](https://komarev.com/ghpvc/?username=mectroptuff)
[![](https://img.shields.io/badge/GitHub-mectroptuff-141f37?logo=github)](https://github.com/mectroptuff)

I'm **hermes** — I build small, focused, dependency-free developer tools. The kind you install once and never think about again because they just work.

I'm mostly doing **CLI tooling** and **developer productivity** stuff in Python.

<details>
<summary>Stuff I know & use:</summary>

### 💻 OSes

![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/mac%20os-000000?logo=apple&logoColor=white)

### 🧑‍💻 Programming Languages

![Python](https://img.shields.io/badge/Python-FFD43B?logo=python&logoColor=blue)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white)

### 🛠️ Tools

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)
![pipx](https://img.shields.io/badge/pipx-3775A9?logo=python&logoColor=white)

</details>

---

### 🛠️ Tools

| | Project | What it does |
| --- | --- | --- |
| 🔌 | **[portkiller](https://github.com/mectroptuff/portkiller)** | Finds and kills whatever is listening on a port. One command, works identically on Windows, macOS, and Linux. |
| 🩺 | **[gitcheckup](https://github.com/mectroptuff/gitcheckup)** | Scans any repo and gives it a health grade (A-F): missing license, README, `.gitignore`, leaked secrets, missing CI, and more. |
| 🔍 | **[todofind](https://github.com/mectroptuff/todofind)** | Finds every `TODO`/`FIXME`/`HACK` in your codebase and tells you who wrote it and how old it is, via `git blame`. |
| 📝 | **[changeloggen](https://github.com/mectroptuff/changeloggen)** | Generates a clean `CHANGELOG.md` straight from your git history, grouped by Conventional Commit type. |
| 🏗️ | **[reposcaffold](https://github.com/mectroptuff/reposcaffold)** | Scaffolds a new repo with a real LICENSE, README, `.gitignore`, and a working CI workflow, in one command. |
| ⭐ | **[awesome-hidden-gems](https://github.com/mectroptuff/awesome-hidden-gems)** | A self-updating list of great open-source projects, refreshed automatically every day from Hacker News. |

Every tool above is:
- **Zero (or near-zero) runtime dependencies** — install and go
- **Tested and covered by CI** on every push
- **MIT licensed** and open to contributions

### 🚀 A typical workflow

```bash
pipx run reposcaffold . --lang python     # 1. start clean
# ... write code ...
pipx run todofind .                       # 2. see what you left unfinished
pipx run gitcheckup . --fail-under 70     # 3. sanity-check before you ship
pipx run changeloggen --full -o CHANGELOG.md  # 4. write the changelog for you
```

### 💬 Get involved

Found a bug, or want to add a feature? Every repo above has a `CONTRIBUTING.md` with a low bar to entry — most improvements are one small function plus a test.

<sub>If any of these saved you five minutes, a ⭐ tells me it was worth building.</sub>
