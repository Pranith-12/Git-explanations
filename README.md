# 🚀 Git & GitHub 

## 📌 What is Git?

Git is a **version control system** that helps you track changes in your code, collaborate with others, and manage different versions of your project.

## 📌 What is GitHub?

GitHub is a **cloud platform** where you can store Git repositories and collaborate with others online.

---

## ⚙️ Installation

### Install Git

Download Git from the official site: https://git-scm.com/

Check installation:

```bash
git --version
```

---

## 👤 Configure Git

Set your username and email (only once):

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

---

## 📁 Initialize a Repository

Create a new Git repository:

```bash
git init
```

---

## 📄 Add Files

Add a specific file:

```bash
git add file.txt
```

Add all files:

```bash
git add .
```

---

## 💾 Commit Changes

Save changes with a message:

```bash
git commit -m "Initial commit"
```

---

## 🌐 Connect to GitHub

Add remote repository:

```bash
git remote add origin https://github.com/your-username/your-repo.git
```

---

## ⬆️ Push Code to GitHub

Push to main branch:

```bash
git push -u origin main
```

---

## ⬇️ Pull Latest Changes

Download updates from GitHub:

```bash
git pull origin main
```

---

## 🔄 Clone a Repository

Copy a repository from GitHub:

```bash
git clone https://github.com/your-username/your-repo.git
```

---

## 🌿 Branching

Create a new branch:

```bash
git branch new-branch
```

Switch branch:

```bash
git checkout new-branch
```

Create & switch:

```bash
git checkout -b new-branch
```

---

## 🔀 Merge Branch

Merge branch into main:

```bash
git checkout main
git merge new-branch
```

---

## 📊 Check Status

View current changes:

```bash
git status
```

---

## 📜 View Commit History

```bash
git log
```

---

## ❌ Undo Changes

Unstage file:

```bash
git reset file.txt
```

Discard changes:

```bash
git checkout -- file.txt
```

---

## 🧠 Tips

* Always commit with meaningful messages
* Pull before pushing to avoid conflicts
* Use branches for new features

---

## 🎯 Example Workflow

```bash
git init
git add .
git commit -m "First commit"
git remote add origin https://github.com/your-username/repo.git
git push -u origin main
```

---

## 📌 Conclusion

Git makes collaboration easy and keeps your project safe. GitHub helps you share and manage your code online.

---

⭐ Feel free to fork and contribute!
