## 通过 Jekyll 建立 github.io 个人页面

通过建立个人页面，了解 **jekyll** 同时，样式上可以采用 *Tailwind* 来进行，不许自己再进行样式编辑

### Scripts

在 `cmd` 处，采用常规的 `bundle exec jekyll server` 来进行本地调试，通过 `--livereload` 进行实时更新页面无需手动刷新页面

### gitHub action

**github action** 可以采用 **jekyll** 脚本自动建立，在提交 *main* 分支到仓库后，可以自动执行