# HMACApplet
I solved the challenge while preserving the existing Git history.

The local repository already had old commits in the `master` and `dev` branches, so I chose to merge the `dev` branch into `master` instead of rebasing, to avoid overwriting the history.

During the merge, there was a conflict in `javaCard.java`. I resolved the conflict manually, keeping the relevant changes from both branches, and completed the merge normally, without using `--force`, `reset --hard`, or any destructive command.

Link to the branch with the result: https://github.com/andreilopes11/HMACApplet/tree/master
