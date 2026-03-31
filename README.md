# This is a repo that was used to test a codex agent and see if it could create a brief writeup about me.

# Git Workflow – hw1-vsk

## 1. Create Files
```bash
touch README.md assistant_draft.md final_version.md
```

## 2. Initialize Repo & First Commit
```bash
git init
git add .
git commit -m "initialized files"
```

## 3. Connect to GitHub & Push
```bash
git branch -M main
git remote add origin https://github.com/Krishnan9074/genaihw1-vsk.git
git push -u origin main
```
> `-u` sets the upstream so future pushes only need `git push`

## 4. Push assistant_draft.md
```bash
git add assistant_draft.md
git commit -m "assistant draft added"
git push
```

## 5. Push final_version.md
```bash
git add final_version.md
git commit -m "added final version"
git push
```

# Here is the git log :
(base) vshreyaskrishnan@Mac hw1-vsk % git log
commit c340a8b665a8a2fe5dbd3c9be5ae3c1bbaa9c982 (HEAD -> main, origin/main)
Author: Krishnan9074 <114993913+Krishnan9074@users.noreply.github.com>
Date:   Mon Mar 30 22:12:31 2026 -0400

    added final version

commit a8fc6bdb9bd23a6ecf721f36211101395a73b6ba
Author: Krishnan9074 <114993913+Krishnan9074@users.noreply.github.com>
Date:   Mon Mar 30 22:11:25 2026 -0400

    assistant draft added

commit 3a4529cde01778abb48c82c2130d3c85dfb7adea
Author: Krishnan9074 <114993913+Krishnan9074@users.noreply.github.com>
Date:   Mon Mar 30 21:34:45 2026 -0400

    initialized files
