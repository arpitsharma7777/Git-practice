# Task 03 — Branching Practice

## 🎯 Goal
Branches banana, switch karna, aur difference samajhna.

---

## 📋 Steps

**Step 1 — Dekho kaun kaun si branches hain:**
```bash
git branch -a
```

**Step 2 — Naya branch banao:**
```bash
git checkout -b feature/apna-naam-experiment
```

**Step 3 — `playground/` folder mein ek file banao:**
Kuch bhi likho — yeh sirf experiment hai:
```bash
# File: playground/apna-naam-notes.md
```
Content:
```markdown
# Mera Playground

Yahan main Git ke saath experiment kar raha hoon.

## Maine aaj yeh seekha:
- 
- 
- 
```

**Step 4 — Commit karo:**
```bash
git add .
git commit -m "feat: add playground notes for [naam]"
```

**Step 5 — Branches ke beech switch karo:**
```bash
git checkout main
# Notice: tumhari file ab nahi dikhegi

git checkout feature/apna-naam-experiment
# File wapas aa gayi!
```

**Step 6 — Push karo:**
```bash
git push origin feature/apna-naam-experiment
```

---

## ✅ Done Kaise Pata Chalega?
GitHub pe `feature/apna-naam-experiment` branch dikh rahi hai.

## 🤯 Mind = Blown Moment
`git checkout main` karte waqt tumhari file "gayab" ho jaati hai —
woh delete nahi hui, bas alag branch pe hai. Yahi branches ka magic hai.