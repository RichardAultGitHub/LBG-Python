Clone:
git clone [REPOSITORY_SSH_URL]

Staging:
# stage all files
git add --all

# stage all files (only if you are at the root of your project)
git add .

# stage selected files: git add [FILES]
git add file_1.txt file_2.txt
git add *.txt

Local Status:
git status

Commiting a Change:
# git commit -m "[COMMIT_MESSAGE]"
git commit -m "initial commit"

Pushing Change:
# git push -u [REMOTE] [REMOTE_BRANCH]
git push -u origin main

Retrieve Remote Changes:
# git pull [REMOTE] [REMOTE_BRANCH]
git pull origin main