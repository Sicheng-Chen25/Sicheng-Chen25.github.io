# 陈思丞个人主页

本站采用 Jekyll、Minimal Mistakes 和 GitHub Pages。中文主页为 `/`，英文主页为 `/en/`。

| 要修改的内容 | 文件 |
| --- | --- |
| 中文正文 | `index.md` |
| 英文正文 | `en/index.md` |
| 姓名、联系方式、网站地址 | `_config.yml` |
| 顶部语言导航 | `_data/navigation.yml` |
| 清华紫配色和项目图片排版 | `assets/css/main.scss` |
| 头像和项目图片 | `assets/images/` |

## 本地预览

使用受支持的 Ruby 及 Bundler，在此目录运行：

```sh
bundle install
bundle exec jekyll serve
```

浏览器访问 `http://localhost:4000/`。要只构建文件，运行 `bundle exec jekyll build`，输出目录为 `_site/`。

## GitHub Pages

将此目录内的文件提交到账号 `Sicheng-Chen25` 的 `sicheng-chen25.github.io` 仓库。到 **Settings → Pages**，将发布源设为 **Deploy from a branch**、**main** 和 **/(root)**。GitHub 会构建 Markdown 和主题，部署完成后从 Pages 设置查看线上网址。

以后修改中英文正文、配置或图片后提交到 `main` 即可触发更新。站点文件会公开，个人简历原件请继续留在维护目录外。

参考 [Hanlin Cai 的建站指南](https://caihanlin.com/blogs/web/) 和 [Minimal Mistakes 安装文档](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)。
