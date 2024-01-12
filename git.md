# Random Questions

### How do I remove a file from git that has already been tracked? Adding it to .gitignore isn't working

Source: [Stackoverflow](https://stackoverflow.com/questions/1274057/how-do-i-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitignore)

To stop tracking a file, we must remove it from the index:

`git rm --cached <file>`

To remove a folder and all files in the folder recursively:

`git rm -r --cached <folder>`
