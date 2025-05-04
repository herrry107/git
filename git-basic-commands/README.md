# Basic Git Commands

**create any folder or directory and run command inside folder**

<pre><code>
#initialise directory for git
git init

#add remote repo to local 
git remote add origin https://github.com/herrry107/git.git

</code></pre>

**pull code from repo to local****

<pre><code>
#this will copy same from repo to local
git pull -u origin main
</code></pre>

<pre><code>
#show git log (commits)
git log
git log --oneline

#show specific commit
git show commit-id
git show commit-id:index.html
</code></pre>

**create file and add to repo**

<pre><code>

git status                      #show git status like file untrack etc 
git add .                       #git add all files (we can also use git add file1.txt)
git commit -m "add file1.txt"   #commit tracked file
git log
git push -u origin main

</code></pre>

![Alt-text](https://github.com/herrry107/git/blob/main/images/git-workflow.png)