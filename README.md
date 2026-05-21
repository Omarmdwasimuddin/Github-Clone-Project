# 🚀 GitHub Clone & Push — Complete Guide

---

## 📥 Step 1 — Project Clone করো

```bash
# GitHub থেকে project clone করো
git clone <github-project-url>

# Project folder এ প্রবেশ করো
cd <project-name>

# VS Code এ open করো
code .
```

> 💡 **Tip:** `<github-project-url>` এর জায়গায় actual repo URL দাও।
> যেমন: `https://github.com/username/my-project.git`

---

## 📦 Step 2 — Dependencies Install করো

```bash
npm install
```

> এটি `node_modules` folder তৈরি করবে — project run করার জন্য দরকারি।

---

## ⚙️ Step 3 — Git Global Config (শুধু **প্রথমবার** দরকার)

```bash
git config --global user.name "Muhammad Wasim Uddin Omar"
git config --global user.email "mdwasimu015@gmail.com"
```

| Field | মান |
|-------|-----|
| `user.name` | তোমার GitHub Profile Name |
| `user.email` | তোমার GitHub Account Email |

> ⚠️ **Note:** একবার global config করলে পরবর্তীতে আর এই command দিতে হবে না।
> সরাসরি `git add .` থেকে শুরু করা যাবে।

---

## 🔼 Step 4 — Changes Push করো

```bash
# সব পরিবর্তন stage করো
git add .

# Commit করো একটি message দিয়ে
git commit -m 'initial commit'

# GitHub এ push করো
git push origin main
```

---

## 🔄 পুরো Process এক নজরে

```
git clone <url>          →   Project নামিয়ে আনো
cd <project-name>        →   Folder এ প্রবেশ করো
code .                   →   VS Code এ খোলো
npm install              →   Packages install করো

── প্রথমবার হলে ──
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

── সবসময় ──
git add .                →   Files stage করো
git commit -m 'message'  →   Commit করো
git push origin main     →   GitHub এ push করো
```

---

## ✅ Quick Checklist

- [ ] Repository clone করা হয়েছে
- [ ] `cd <project-name>` দিয়ে folder এ ঢোকা হয়েছে
- [ ] `npm install` রান করা হয়েছে
- [ ] Git global config করা হয়েছে (প্রথমবার)
- [ ] `git add .` → `git commit` → `git push` করা হয়েছে

---

> 📌 **মনে রাখো:** `git push origin main` — এখানে `main` হলো branch name।
> কোনো কোনো পুরনো project এ `master` হতে পারে।
