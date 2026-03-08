# Task 04 — Pull Request Raise Karo

## 🎯 Goal
Task 02 ki branch se PR raise karo aur review process samjho.

---

## 📋 Steps

**Step 1 — GitHub pe apna repo kholo**

**Step 2 — "Compare & pull request" button dikhega** tumhari branch ke liye.
Agar nahi dikh raha:
- "Pull requests" tab → "New pull request"
- base: `main` ← compare: `feature/apna-naam-intro`

**Step 3 — PR form bharo:**
```
Title: feat: add intro for [Tumhara Naam]

Description:
## Kya kiya?
- `members/` folder mein apni introduction file add ki

## Kaise test karein?
- `members/apna-naam.md` file dekho

## Notes
- Pehla PR hai, feedback welcome hai 🙏
```

**Step 4 — "Create pull request" click karo**

**Step 5 — Arpit ka review aayega** — changes maange toh:
```bash
# Same branch pe changes karo
git add .
git commit -m "fix: address review comments"
git push origin feature/apna-naam-intro
# PR automatically update ho jaayega
```

---

## ✅ Done Kaise Pata Chalega?
PR "Open" status mein dikh raha hai GitHub pe.

## 💡 PR Rules (Yaad Rakhna)
- ❌ "Please merge karo bhai" mat likho description mein
- ✅ Clearly likho — kya kiya, kyun kiya
- ✅ Review comments pe defensive mat hona