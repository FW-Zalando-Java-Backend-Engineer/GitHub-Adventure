# 🌟 **Your First Git + GitHub Adventure!**  
Welcome to the world of Git and GitHub! You're going to complete **4 fun exercises** using Git and a few Bash commands. Don’t worry—**everything is explained step by step**. You’ve got this!

---

## 🧩 What You'll Learn:
- How to use basic **Git commands**: `init`, `add`, `commit`, `push`
- How to use **Bash commands**: `touch`, `mkdir`, `echo`, `cat`, `mv`, `cp`
- How to create your own **GitHub repo** and push your project to it
- How to **share your work** by updating a `README.md` file

---

## 📌 BEFORE YOU START
Make sure you have:
✅ Git installed – if not, download from [git-scm.com/downloads](https://git-scm.com/downloads)  
✅ A GitHub account – if not, sign up free at [github.com](https://github.com)  
✅ A code editor like IntelliJ IDEA (optional, but helpful)  
✅ A big smile 😊

---

## 💥 Step 1: Create Your Own GitHub Repo (Super Easy!)

You’ll do this **for each of the 4 exercises**.

### 🔧 How to Create a Repo:
1. Go to 👉 [https://github.com](https://github.com)
2. Click the **+** in the top-right corner → Choose **“New repository”**
3. Give it a fun name, like:
   - `git-garden`
   - `clone-wars`
   - `organize-life`
   - `journal-machine`
4. Set it to **Public**
5. **Do NOT** check “Add README”
6. Click **Create repository**
7. You’ll now see a page with some commands. You’ll come back to this after writing some code locally!

---

## 🧠 Step 2: Do Each Exercise (Locally)

You’ll now do the work on your **computer**, then push it to GitHub.

---

## 🌱 **Exercise 1: My Git Garden**
Create a garden using files and track them with Git!

### 💻 Steps:
```bash
# Step 1: Make a project folder
mkdir git-garden
cd git-garden

# Step 2: Start Git
git init

# Step 3: Create flower files
touch rose.txt tulip.txt sunflower.txt

# Step 4: Add flower messages
echo "🌹 I am a rose" > rose.txt
echo "🌷 I am a tulip" > tulip.txt
echo "🌻 I am a sunflower" > sunflower.txt

# Step 5: Track your files
git add .
git commit -m "Plant 3 flowers in my garden"
```

---

## 🚀 **Exercise 2: Clone Wars**
Fix a file from a starter repo!

### 💻 Steps:
1. Your teacher will give you a **GitHub link**.
2. Clone the repo:
```bash
git clone https://github.com/yourteacher/starter-repo.git
cd starter-repo
```
3. Read the file:
```bash
cat mission.txt
```
4. Fix any typos:
```bash
echo "This is your mission: Fix the typo and commit." > mission.txt
```
5. Commit it:
```bash
git add mission.txt
git commit -m "Fix typo in mission"
```

---

## 📦 **Exercise 3: Organize Your Life**
Use folders and files to get your “digital life” together.

### 💻 Steps:
```bash
# Step 1: Create the project
mkdir organize-life
cd organize-life
git init

# Step 2: Make two files
touch todo.txt notes.txt
echo "1. Learn Git" > todo.txt
echo "Some notes here..." > notes.txt

# Step 3: Make folders and organize
mkdir tasks logs
mv todo.txt tasks/
cp notes.txt logs/log1.txt

# Step 4: Track and commit
git add .
git commit -m "Organize life into folders"
```

---

## 📝 **Exercise 4: Journal Time Machine**
Make a journal and track entries like a time traveler!

### 💻 Steps:
```bash
mkdir journal-machine
cd journal-machine
git init
touch journal.txt

# Add entries each day
echo "Day 1: Learned Git basics" >> journal.txt
git add journal.txt
git commit -m "Add Day 1 entry"

echo "Day 2: Practiced Bash commands" >> journal.txt
git add journal.txt
git commit -m "Add Day 2 entry"
```

---

## ☁️ Step 3: Push Your Project to GitHub

After finishing each project:

### 📌 Push to GitHub:
1. Go to your GitHub repo page (like `https://github.com/yourusername/git-garden`)
2. Copy the URL
3. Then run:
```bash
git remote add origin https://github.com/yourusername/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

🎉 Done! Your project is live on GitHub!

---

## 📣 Step 4: Share Your Work (Update the Classroom README)

In the **GitHub Classroom repo** (where you got these instructions), open the file called `README.md` and add links to your 4 projects.

### Example:
```markdown
# 🌟 My Git Projects

## 🌱 Git Garden
🔗 https://github.com/yourusername/git-garden

## 🚀 Clone Wars
🔗 https://github.com/yourusername/clone-wars

## 📦 Organize Your Life
🔗 https://github.com/yourusername/organize-life

## 📖 Journal Time Machine
🔗 https://github.com/yourusername/journal-machine
```

✅ Make sure your repos are **public** so your teacher can see them.

---

## 🎉 You're a Git Star!

You’ve created:
✅ Your own GitHub repositories  
✅ Files and folders using Bash  
✅ Versioned your work with Git  
✅ Published your code to GitHub  
✅ Shared it all like a pro

👏 That’s amazing!

---

## 📚 References:
- [Git Official Site](https://git-scm.com)
- [GitHub Docs](https://docs.github.com/)
- [Command Line Bash Cheat Sheet](https://github.com/LeCoupa/awesome-cheatsheets/blob/master/languages/bash.sh)

