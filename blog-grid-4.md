# Style : Blog Grid

> **Note** You can provide how many columns to render per row like `blog-grid-{number}`

```yaml
  - name: "📚  Hashnode Updater"
    uses: "varunsridharan/action-hashnode-blog@main"
    with:
      USERNAME: 'your-username'
      COUNT: 12
      STYLE: "blog-grid-4" # you can increase / decrease the no of columns to render by changing the value 4
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

---

<!-- HASHNODE_BLOG:START -->
<!-- HASHNODE_BLOG:END -->