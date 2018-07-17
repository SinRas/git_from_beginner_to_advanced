# [Advanced Git Tutorial][1]
Teaches How to use `rebase` command. $$$


# [GitHub Tutorial][2]
Teaches how to set `gitconfig` paramters and change files.
- `--local`, `--global`, `--system` tags. Local is repository scope, global is current git user scope, system is all system user scope.
- `name`, `email`, `core.autocrlf` parameters
- `push.default`, `pull.default`
- `pull` is application of `fetch` and `merger`
- `pull --rebase` applies `fetch` and `rebase`
- Better to use `git pull --rebase` instead of `git pull`
- `git config --global pull.rebase true`
- `color.ui`
- `git status -s` silent mode.
- `git config --global alias.s "status -s"` => `git s` will now do `git status -s`
- `git config --global alias.lg "log --oneline --decorate --all --graph"` => `git lg` now does the "git log --oneline --decorate --all --graph"
-

# [Git & GitHub Crash Course for Beginners][3]
Good tutorial of how to do simple things. $$$



# [Getting Started - Git Basics][4]
- Other version controls store are 'Delta-Based' which means that they store the difference. Git is 'Stream of Snapshots' which will store new files and link to unchanged files.
- Nearly every operation is local. This enables great speed in comparison with other CVCS which had to connect to net. ( ... more emphasis on the fact that things are stored offline :| )
- Git works with checksums for everything! So integrity is not an issue.
- Nearly everything stores data therefor undoable if necessary.
- Git has three main states. _commited_, _modified_, and _staged_.
    - _commited_ means that the data is safely stored in your local databse
    - _modified_ means that you have changes the file but have not commited it to your database yet
    - _staged_ means that you have marked a modified file in its current version to go into your next commit snapshot













[1]: https://www.youtube.com/watch?v=6nolZKpiG_w
[2]: https://www.youtube.com/watch?v=KMH1mImE0UE
[3]: https://www.youtube.com/watch?v=SWYqp7iY_Tc
[4]: https://git-scm.com/book/en/v2/Getting-Started-Git-Basics