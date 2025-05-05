# Git Conflict

When same files having different content in different branches, if you do merge, conflict occurs (Resolve conflict then add and commit)

# Git Stashing

Suppose you are Implementing a new feature for your product. Your code is in progress and suddenly a customer escalation comes because of this, you have to keep aside your new feature work for few hours.

You can't commit your code partial code and also cannot throw away your changes so you need some temporary storage, when you store your partial changes and later on commit it.

To stash an item (only applies to modified fiels not new files)

git stash is used to temporarily save changes in your working directory that you don’t want to commit yet. It allows you to switch branches or pull in changes without losing your current work.

**Save changes**
<pre><code>
git stash
</code></pre>

or with a **custom message**
<pre><code>
git stash save "your message"
</code></pre>

**List stashes**
<pre><code>
git stash list
</code></pre>

Apply latest stash
<pre><code>
git stash apply
</code></pre>

Or a specific stash:
<pre><code>
git stash apply stash@{2}
</code></pre>

Pop (apply + remove) latest stash
<pre><code>
git stash pop
</code></pre>

Or a specific one:
<pre><code>
git stash pop stash@{1}
</code></pre>

Drop a specific stash
<pre><code>
git stash drop stash@{0}
</code></pre>

Clear all stashes
<pre><code>
git stash clear
</code></pre>