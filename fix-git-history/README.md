# Fix GitHub history #

Fix when git config user.name and user.email are not set but commits done.

## Instructions ##

* Based on https://help.github.com/articles/changing-author-info/
* Clone your repository with -bare option: git clone --bare https://github.com/user/repo.git
* Change OLD_EMAIL, CORRECT_NAME and CORRECT_EMAIL variables in script.sh.
* Run script.sh at repository root.
* Run git push --force --tags origin "refs/heads/*" in terminal.
* Done!
