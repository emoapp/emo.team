# Emo Web.

```sh
git clone https://github.com/emoapp/web
git submodule update --init
```

编写草稿，本地预览无误后，发起 PR：

```sh
hugo server --disableFastRender -p 2000
```

使用 `npx gh-pages -d public` 发布 GitHub Pages

---

DNS 配置见

- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
