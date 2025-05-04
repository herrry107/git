# Branch
**A Git branch is a lightweight movable pointer to a commit in a Git repository. It allows you to work on different versions of a project simultaneously without affecting the main codebase.**

**Simple Definition**: A Git branch is a separate line of development in a Git repository.

Key Points:
- The default branch is usually called main or master.
- Branches let developers isolate work, such as features, bug fixes, or experiments.
- You can create, switch, merge, and delete branches.

Common Git branch commands:

See all branch
<pre><code>
git branch
</code></pre>

Create new branch
<pre><code>
#git branch branch-name
git branch feature1
</code></pre>

To switch branch
<pre><code>
#git checkout branch-name
git checkout feature1
</code></pre>

Delete branch
<pre><code>
#git branch -D branch-name
#git branch -d branch-name
git branch -d feature1
</code></pre>

# Merge Git Branch

**git merge** is a command in Git used to combine the changes from one branch into another. It’s most commonly used to bring feature branches back into the main development branch (like **main** or **master**).

suppose we have some changed in **branch feature** now we want to merge our **feature branch** changes into **main branch**, so first we checkout to **main branch** after that we run merge command 

**feature-branch -> main-branch**
<pre><code>
git checkout main        #go to main branch
git merge feature1       #merge feature branch to main
git branch -d feature1   #(optional) if we want to delete branch feature
git log                  #To verify merge
</code></pre>

![git-reset](https://github.com/herrry107/git/blob/main/images/branch-strategies.png)


