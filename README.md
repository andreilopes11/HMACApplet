# HMACApplet
I solved the challenge while preserving the existing Git history.

The local repository already had old commits in the `master` and `dev` branches, so I chose to merge the `dev` branch into `master` instead of rebasing, to avoid overwriting the history.

During the merge, there was a conflict in `javaCard.java`. I resolved the conflict manually, keeping the relevant changes from both branches, and completed the merge normally, without using `--force`, `reset --hard`, or any destructive command.

Link to the branch with the result: https://github.com/andreilopes11/HMACApplet/tree/master

```
$ git log --oneline --graph --decorate --all --max-count=10
*   5c385ea (HEAD -> master, origin/master) Merge branch 'dev'
|\  
| * f94bad8 (dev) feat: remove case 3 and 4
| * d2edb79 feat: add ins_dev variable
* | a6bceea feat: remove case 2 and 5
* | 4466832 feat: add ins_master variable
|/  
* f73b1dd init commit
* 0a69547 (origin/main) Initial commit
```
