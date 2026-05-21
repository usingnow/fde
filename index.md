---
title: Home
layout: home
---

欢迎访问 **FDE 采恪智创** 文档站。本站基于 [Just the Docs] 主题，部署于 [GitHub Pages]，域名 [fde.usingnow.tech](https://fde.usingnow.tech)。

## Callouts 样例

以下展示 `_config.yml` 中配置的五种提示框（浅色背景 + 主题色 `-000`/`-100` 色阶）。写法见 [Configuration · Callouts](https://just-the-docs.com/docs/configuration/#callouts)，色阶见 [Color Utilities](https://just-the-docs.com/docs/utilities/color/)。

{: .highlight }
本地预览：`bundle exec jekyll serve`，浏览器打开 http://localhost:4000 。

{: .note }
说明类信息适合用 `note`，边框为紫色，与站点品牌色一致。

{: .important }
重要：推送到 `main` 分支后，GitHub Actions 会自动构建并发布到 Pages。

{: .new }
新功能：已支持自定义域名与侧边栏品牌文案（采恪智创 / UsingNow·AI）。

{: .warning }
警告：若样式未更新，多为浏览器缓存，请用无痕窗口或强制刷新后再查看。

多行内容可使用 blockquote 写法：

> {: .note }
> 第一行说明文字。
>
> 第二行可继续补充细节。

---

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.脚注示例[^2]。

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).
[^2]: 随机脚注：采恪智创的文档站就像一杯温茶——不烫嘴，但能让你在深夜改配置时依然保持清醒。

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
