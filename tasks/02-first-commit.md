# Task 02 — Pehla Commit Karo

## 🎯 Goal
Ek file banao, stage karo, commit karo, push karo.

---

## 📋 Steps

**Step 1 — dev branch pe aao:**
```bash
git checkout -b feature/apna-naam-intro
```
Example: `feature/arpit-intro`, `feature/banda2-intro`

**Step 2 — Apni introduction file banao:**
```bash
# `members/` folder mein apni file banao
# Naam: apna-naam.md
```

File ka content yeh rakho:
```markdown
# Hello, main hoon [Tumhara Naam]!

- Role: [Frontend / Backend / DevOps / Design]
- Ek fun fact: [kuch bhi likho]
- Mujhe Git mein sabse pehle yeh sikhna hai: [likho]
```

**Step 3 — Status check karo:**
```bash
git status
```
Tumhari file `Untracked files` mein dikhegi.

**Step 4 — Stage karo:**
```bash
git add members/apna-naam.md
```

**Step 5 — Commit karo:**
```bash
git commit -m "feat: add intro for [tumhara naam]"
```

**Step 6 — Push karo:**
```bash
git push origin feature/apna-naam-intro
```

---

## ✅ Done Kaise Pata Chalega?
GitHub pe tumhari branch dikh rahi hai with your file.

## 💡 Tip
`git log --oneline` se apna commit history dekh sakte ho.