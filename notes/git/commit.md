=== Commit ===
In Git, commit are a snapshot of the changes you made. When you remove and add a files, it'll be contained to a commit.

#### Adding new files to a Commit
The `git add FILENAME` commands adds FILENAME into a commit. If you don't add anything, the changes you've made won't be included into the commit.

#### Creating new Commit
To create a new commit, use the `git commit -m "MESSAGE"`.
You can signed your commit message with GPG via the `git commit -S -m` the GPG key must be set via the `git config --global user.siginingkey KEY` command.

#### Stage modified or deleted files to a Commit
To only commit the modified or deleted files, use the `git commit -a -m MESSAGE`

#### Change last commit/delete old commit and replace with a new one
use the `git commit --amend -m MESSAGE`
