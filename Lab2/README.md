# Lab 2: Pushing and Cloning a Repository

**Course:** BCS352, HTML and CSS Introduction Lab (Invertis University, Bareilly)
**Name:** Priyanshi Sharma | **Roll No:** BCS2025582

**Aim:** Send your commits to a second repository on your computer and make a copy of it with clone.

## Tasks

| # | What to do | Commands |
|---|------------|----------|
| 1 | Create a bare repository and add it as `origin` | `git init --bare ../html-remote`, `git remote add origin ../html-remote`, `git remote -v` |
| 2 | Push your commits | `git push origin main` (use `master` if `git status` says `On branch master`) |
| 3 | Clone and check the history | `cd ..`, `git clone html-remote html-copy`, `cd html-copy`, `git log --oneline` |


