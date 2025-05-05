# git
Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously, keeps a history of changes, and helps coordinate work through branching and merging.

**Introduction to git**

# CVCS(Centralized Version Control System)
- In CVCS, a client need to get local copy of source from server, do that changes and commit those changes to central source on server.
- CVCS system are easy to learn & setup.
- Working on branches is difficult in CVCS. Developer ofter faces merge conflict
- CVCS system need internet.
- CVCS is slower as every command need to communicate with server.
- If CVCS server is down, developer cannot work.

# DVCS(Distibuted Version Control System)
- In DVCS, each cient can have a local branch as well and have a complete history on it, Client need to push the changes to branch which will then be pushed to server repository.
- DVCS systems are difficult for beginners. Multiple commands needs to be remembered.
- Working on branches is easier in DVCS developer faces less conflict.
- DVCS system are working fine on offline mode as a client copies the entire repository on their local machine.
- It is faster because it uses offline.
- If DVCS server is down, developer can work using their local copies.

# Read All Git Docs by these sequence
[1) Git Basic Commands](https://github.com/herrry107/git/tree/main/git-basic-commands)

[2) Git Branch](https://github.com/herrry107/git/tree/main/branch)

[3) Git Conflict and Stashing](https://github.com/herrry107/git/tree/main/conflict-stashing)

[4) Git Reset](https://github.com/herrry107/git/tree/main/reset)

[5) Git Revert](https://github.com/herrry107/git/tree/main/revert)

[6) Git Revert](https://github.com/herrry107/git/tree/main/tags)