__GIT CONFIG__
git config --system --edit
git config --global --edit
git config --local --edit
git config --global core.editor <editor>
git config --global user.naem <name>
git config --global user.email <email>
git config --list
git config --list --show-origin
__GIT BASICS__
git init
git status
git add <untrakced>
git commit #--> open editor
git commit <file> -m <message>
git log
git clone <url>
git reset
git reset <file>
git status -s
.gitignore:
	how to write .gitignore file<https://www.atlassian.com/git/tutorials/saving-changes/gitignore>

Hint: tracked file not ignored when set to ignore

git diff
git diff --staged
git difftool --staged
git rm <file>
git rm -f <file> # erease form hard disk and git repo
git rm --cached <file> #erease only from git repo
git checkout <file> # return to last snapshot hint: Not revertible
git mv <file>
git log
git log -p
git log -p -<num>
git log --stat
git log --pretty
git log --pretty=oneline
git log --pretty=format:"%h %an"
git log --since="2.years"
git log -S <expression>
git --amend
git --amend --no-edit
git remote -v
git remote
git remote add <remote-name> <url>
git fetch <remote-name>
git remote remove <remote-name>
git branch -a
git push
git push <remote> <branch>
git push --up-stream <remote> <branch>
git push -u <remote> <branch>
git remote show origin
git tag
git tag <version>
git tag  -a <version> -m <message>
git show <tagsname>
git push <remote> <tagsname>
git push origin --tags
git tag --delete
git tag | xrags git tag --delete

__GIT BRANCHING__
git branch
git checkout <branch-name>
