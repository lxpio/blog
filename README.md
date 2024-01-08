# lxpio blog

对我域名地址： https://blog.lxpio.com/

参考 https://gohugo.io/getting-started/quick-start/

```bash
# 创建新的文章
hugo new content posts/my-first-post.md
```

本地服务

```bash
hugo server -D  --baseURL http://localhost:1313/
```

完成文档后直接推送到 github ，workflow 会自动创建 gh-pages 分支

```bash
git add .
git commit -m "my commit"
git push

#

```
