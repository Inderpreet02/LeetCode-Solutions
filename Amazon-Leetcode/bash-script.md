# Approach 1:

```bash
#!urs/bin/bash

cd /d/Dev/LeetCode-Solutions

git add .

DATE=${date}

git commit -m "changes made on $DATE"

git push --set-upstream origin master

command && notify-send "It worked and all changes are commited"

```