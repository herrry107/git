The revert command helps us to undo an existing commit.

It doesn't delete any data in the process instead rather git creates a new commit with the included files reverted to their previous state. So, your version control history moves forward while the state of your file moves backward.

<pre><code>
#git revert commit-id
git revert ebf657b
</code></pre>