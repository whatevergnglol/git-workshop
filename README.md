# Git Workshop

A small repo for learning Git and GitHub.

## Before the session

1. Click the green **Use this template** button at the top of this page,
   then **Create a new repository**. Name it `git-workshop`. Keep it Public.
   You now have your own copy.

2. Copy it to your laptop:

   ```
   git clone https://github.com/YOUR-USERNAME/git-workshop.git
   cd git-workshop
   ```

3. Tell Git who you are (once, ever):

   ```
   git config --global user.name "Your Name"
   git config --global user.email "your-github-email@example.com"
   git config --global pull.rebase false
   ```

4. Check that you can push. Open `notes.md`, type anything after
   "Favourite language:", save, then run:

   ```
   git add notes.md
   git commit -m "test"
   git push
   ```

   If the last command succeeds, you are ready.
   If it asks for a password and then fails, message the organiser —
   this needs fixing before the session, not during it.

## During the session

We will use the commands below. Don't memorise them.

```
git clone <url>          copy a repo to your laptop
git switch -c <name>     make a new branch
git status               what has changed
git add <file>           choose what goes in the next snapshot
git commit -m "..."      take the snapshot
git push                 send your snapshots to GitHub
git switch main          move to the main branch
git pull                 bring GitHub's changes down to your laptop
```