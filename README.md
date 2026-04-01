https://git-scm.com/docs

📁 Setup & Config
git init
git clone <url>
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
📌 Tracking Changes
git status
git add <file>
git add .
git restore <file>
👉 Brutal truth:
If you don’t understand git add, you don’t understand Git.
💾 Committing
git commit -m "message"
git commit --amend
👉 Amend is dangerous if you don’t know history rewriting.
🔍 Inspecting
git log
git log --oneline --graph --all
git diff
🌿 Branching (MOST IMPORTANT)
git branch
git branch <name>
git checkout <branch>
git switch <branch>
git merge <branch>
👉 If you’re weak in branching, you’re not job-ready.
🔥 Rewriting History (Advanced but essential)
git rebase
git rebase -i HEAD~3
git reset --soft HEAD~1
git reset --hard HEAD~1
👉 This is where most devs panic. You shouldn’t.
🌐 Remote (Real-world usage)
git remote add origin <url>
git push
git pull
git fetch
👉 Understand this clearly:
pull = fetch + merge
fetch is safer
