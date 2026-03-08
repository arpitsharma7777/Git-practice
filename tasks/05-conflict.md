# Task 05 — Conflict Resolve Karo (Boss Level 🔥)

## 🎯 Goal
Intentionally conflict create karo aur khud resolve karo.

---

## 📋 Setup (Arpit karega yeh)
Arpit ne `conflict-practice/shared-file.md` mein already kuch content likha hai.

---

## 📋 Steps

**Step 1 — Fresh branch lo:**
```bash
git checkout main
git pull origin main
git checkout -b feature/apna-naam-conflict
```

**Step 2 — `conflict-practice/shared-file.md` edit karo:**
File mein `[TUMHARA NAAM KI JAGAH]` wali line dhundo aur apna content likho.

**Step 3 — Commit + push karo:**
```bash
git add .
git commit -m "feat: add my line in shared file"
git push origin feature/apna-naam-conflict
```

**Step 4 — Arpit ek aur banda ka PR pehle merge karega** — tab tumhara conflict aayega.

**Step 5 — Conflict fix karo:**
```bash
git checkout feature/apna-naam-conflict
git pull origin main
# CONFLICT! 
git status  # konsi file dekho
```

File kholo — yeh dikhega:
```
<<<<<<< HEAD
  tumhara content
=======
  doosre banda ka content
>>>>>>> main
```

**Dono rakhna hai yahan — doosre ka mat hatao!**
Remove karo sirf: `<<<<<<<`, `=======`, `>>>>>>>`
```bash
git add conflict-practice/shared-file.md
git commit -m "fix: resolve merge conflict in shared file"
git push origin feature/apna-naam-conflict
```

---

## ✅ Done Kaise Pata Chalega?
`git log --oneline` mein "fix: resolve merge conflict" dikh raha hai.

## 🏆 Agar Yeh Kar Liya
Tum officially "conflict se darte nahi" wale category mein aa gaye.