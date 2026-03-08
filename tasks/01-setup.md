# Task 01 — Setup Verify Karo

## 🎯 Goal
Confirm karo ki Git properly configured hai tumhare laptop pe.

---

## 📋 Steps

**Step 1 — Git version check karo:**
```bash
git --version
```
Expected output: `git version 2.x.x`

**Step 2 — Apna naam aur email set karo:**
```bash
git config --global user.name "Tumhara Naam"
git config --global user.email "tumhari@email.com"
```

**Step 3 — Confirm karo:**
```bash
git config --list
```
`user.name` aur `user.email` dikhna chahiye.

**Step 4 — Repo clone karo:**
```bash
git clone https://github.com/arpitsharma7777/linksutra-git-practice.git
cd linksutra-git-practice
```

**Step 5 — Sab files dekho:**
```bash
ls
```

---

## ✅ Done Kaise Pata Chalega?
Repo clone ho gayi aur `ls` mein README.md dikh raha hai.

## ❓ Problem Aaye Toh
`git config --list` mein `user.name` nahi dikh raha?
→ Step 2 dobara karo with correct details.