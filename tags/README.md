# Tags

The git tag command is used to create, list, delete, or verify tags in Git. Tags are like bookmarks that point to specific commits—commonly used to mark release versions (e.g., v1.0, v2.0).

Tag operation allows giving meaningful names to a specific version in the repository.

To apply tag
<pre><code>
#git tag -a tagname -m message commit-id
git tag -a v1 -m "v1 added" 4c8e94c
</code></pre>

Show all tags
<pre><code>git tag</code></pre>

To see particular commit content
<pre><code>git show tag-name</code></pre>

To delete tag
<pre><code>git tag -d tag-name</code></pre>

