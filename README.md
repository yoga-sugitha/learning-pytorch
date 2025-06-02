
---

````markdown
# 🧾 Git Commands Cheat Sheet
''''
## 1. 🔍 Check Repo Status

```bash
git status
```

Shows changes, untracked files, and branch info.

---

## 2. ➕ Add Files to Staging Area

Add a specific file:

```bash
git add filename.ipynb
```

Add all changes:

```bash
git add .
```

---

## 3. ✅ Commit Changes

```bash
git commit -m "Describe what you changed"
```

---

## 4. ⬆️ Push to GitHub

```bash
git push origin main
```

Replace `main` with your branch name if different.

---

## 5. ⬇️ Pull Latest Changes

```bash
git pull origin main
```

Use this if someone (or you from another machine) pushed changes.

---

## 6. 🌿 Create a New Branch

```bash
git checkout -b new-feature
```

Useful when working on a new feature without affecting `main`.

---

## 7. 🔄 Switch Branches

```bash
git checkout main
```

---

## 8. 📜 View Commit History

```bash
git log --oneline --graph --decorate --all
```

A compact, visual summary of commits and branches.

---


