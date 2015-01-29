
如果我没理解错的话


Github 会自动把 username.github.io 这个 repo 启动为 *Github Pages* 的 Server Host

如果没有这个 repo 但是有的 repo 开了独立子分支 gh-pages

```
	git checkout --orphan gh-pages
```

那么也会启动  Github Pages 的 Server，并且自动拉到 username.github.io/repo-name/ 下，
这时候因为 root 目录下没有 index.html ，所以会给个 Github 404


以上。
