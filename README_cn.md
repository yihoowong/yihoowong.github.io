<div align="center">
  <br>

  <a href="https://github.com/jeffreytse/jekyll-theme-yat">
    <img alt="jekyll-theme-yat →~ jekyll" src="https://user-images.githubusercontent.com/9413601/106478481-346fdf00-64e4-11eb-9385-1ab5329c3234.png" width="600">
  </a>

  <h1>JEKYLL YAT 主题</h1>

</div>

<h4 align="center">
  优雅创作者的 <a href="https://jekyllrb.com/" target="_blank"><code>Jekyll</code></a> 主题
</h4>

<p align="center">
  <a href="https://jeffreytse.github.io/jekyll-theme-yat">
    <img src="https://github.com/jeffreytse/jekyll-theme-yat/workflows/Github%20Pages/badge.svg"
      alt="Github Pages" />
  </a>

  <a href="https://badge.fury.io/rb/jekyll-theme-yat">
    <img src="https://badge.fury.io/rb/jekyll-theme-yat.svg"
      alt="Gem Version" />
  </a>

  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-brightgreen.svg"
      alt="License: MIT" />
  </a>

  <a href="https://liberapay.com/jeffreytse">
    <img src="https://img.shields.io/liberapay/goal/jeffreytse.svg?logo=liberapay"
      alt="Donate (Liberapay)" />
  </a>

  <a href="https://patreon.com/jeffreytse">
    <img src="https://img.shields.io/badge/support-patreon-F96854.svg?style=flat-square"
      alt="Donate (Patreon)" />
  </a>

  <a href="https://ko-fi.com/jeffreytse">
  <img height="20" src="https://www.ko-fi.com/img/githubbutton_sm.svg"
  alt="Donate (Ko-fi)" />
  </a>
</p>

<div align="center">
  <sub>Built with ❤︎ by
  <a href="https://jeffreytse.net">jeffreytse</a> and
  <a href="https://github.com/jeffreytse/jekyll-theme-yat/graphs/contributors">contributors </a>
  </sub>
</div>

<br>

相遇即是缘！很高兴你发现这个 [Jekyll][jekyll] 主题。 本 *YAT (另一个主题 )* 是一个现代化的响应式主题。对于创作者和推文来说，它非常清晰、干净且整洁。**如果你是一个优雅的创作者，专注于内容，那就不要错过它。**

<p align="center">
喜欢这个优雅的主题吗？你可以给<a href="https://github.com/jeffreytse/jekyll-theme-yat">原作者</a> 一个star或者赞助他们！<br>
我非常重视您的大力支持并致以诚挚的感谢！
</p>

<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/91842897-6a840b00-ec87-11ea-95ca-52abcc1ac063.png" alt="demo-screenshot" width="100%"/>

</p>

<h4 align="center">横幅</h4>

<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/123897812-ae729a00-d996-11eb-96b8-b76ba926f555.gif" alt="demo-screenshot" width="100%"/>

</p>

## 特征

- 支持漂亮的**夜间模式**
- 现代化的响应式网页设计
- 包含 `home`, `post`, `tags`, `archive` 和 `about` 的完整布局
- 使用字体 awesome 5 作为图标
- 带有图片和视频的精美页面横幅
- 基于 [highlight.js][highlight-js] 的精美语法突出显示
- 基于 [PhotoSwipe 5][photoswipe-5] 的精美图片库预览器
- 基于 [Jekyll Feed][jekyll-feed] gem 的 RSS 支持
- 利用 [Jekyll Seo Tag][jekyll-seo-tag] gem 优化搜索引擎
- 基于 [Jekyll Sitemap][jekyll-sitemap] gem 的站点地图支持
- 基于 [Jekyll Spaceship][jekyll-spaceship] gem 的复杂且灵活的桌面支持
- 基于 [Jekyll Spaceship][jekyll-spaceship] gem 的 MathJAX 和 LaTeX 的可选性支持
- 基于 [Jekyll Spaceship][jekyll-spaceship] gem 的媒体支持（Youtube、Spotify等）
- 基于 [Jekyll Spaceship][jekyll-spaceship] gem 的图表支持（PlantUML, Mermaid）
- 支持谷歌翻译
- 支持新推文标签
- 支持锁定推文标签

其他的请访问主题网站 [Live Demo][yat-live-demo] 了解。

## 安装

有三种方式进行安装:

- 以 [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes) 安装
- 以 [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) 安装（兼容GitHub Pages）
- 分叉/直接复制所有主题文件到您的项目

### 基于 Gem 主题的方法

将本行添加至您 Jekyll 站点的 `Gemfile` 中：

```ruby
gem "jekyll-theme-yat"
```

并将本行添加至您 Jekyll 站点的 `_config.yml` 中：

```yaml
theme: jekyll-theme-yat
```

然后执行：

```bash
$ bundle
```

或者自行安装：

```bash
$ gem install jekyll-theme-yat
```

### 使用 GitHub Pages 远程主题的方法

远程主题类似于基于 Gem 的主题, 但并不需要修改 `Gemfile` 或白名单，因此非常适合使用 GitHub Pages 托管的网站。

安装:

将本行添加至您 Jekyll 站点的 `Gemfile` 中：

```ruby
gem "github-pages", group: :jekyll_plugins
```

并将本行添加至您 Jekyll 站点的 `_config.yml` 中：

```yaml
# theme: owner/name --> Don't forget to remove/comment the gem-based theme option
remote_theme: "jeffreytse/jekyll-theme-yat"
```

然后执行:

```bash
$ bundle
```

### 分叉/克隆项目

您需要更新 github 工作流文件 `.github/workflows/build-jekyll.yml` 的选项，特别是确保 `jekyll_baseurl` 的值正确。

### GitHub Pages 解除限制

GitHub Pages 以 `safe` 模式运行且仅允许 [一组列入白名单的插件/主题](https://pages.github.com/versions/)。 **换句话说，第三方 Gem 无法正常运行**。

想要在 GitHub Pages 中不受限地使用第三方 Gem :

此处有一个名为 [jekyll-deploy-action](https://github.com/jeffreytse/jekyll-deploy-action) 的 GitHub Action, 能够方便地部署 Jekyll 站点。 👍

## 用法

添加或更新您可用的布局、内容、sass 和/或 assets 文件夹。

## 开发

要设置环境以开发本主题，请运行 `bundle install`。

您的主题设置就像普通的 Jekyll 网站一样！要测试您的主题，请运行 `bundle exec jekyll serve` 并打开浏览器地址 `http://localhost:4000`。这将使用您的主题启动 Jekyll 服务器。像往常一样添加页面、文档、数据等来测试您的主题内容。当您对主题和内容进行修改时，您需要像往常一样刷新浏览器页面后才能看到修改后的内容。

当您的主题发布以后，只有使用 Git 跟踪的 `_data`、`_layouts`、`_includes`、`_sass` 和 `assets` 中的文件才会被绑定使用。要向 Gem 主题添加自定义目录，请编辑 `jekyll-theme-yat.gemspec` 中相应的正则表达式。

## 贡献

非常感谢您的问题和拉取请求。如果您以前从未为开源项目做过贡献，我非常乐意向您介绍如何创建拉取请求。

您可以通过 [创建一个问题](https://github.com/jeffreytse/jekyll-theme-yat/issues/new) 描述您要解决的问题，我们将从那里开始。

## 许可

本主题通过 [MIT license](https://opensource.org/licenses/mit-license.php) © JeffreyTse 授权。

<!-- External links -->

[jekyll]: https://jekyllrb.com/
[yat-git-repo]: https://github.com/jeffreytse/jekyll-theme-yat/
[yat-live-demo]: https://jeffreytse.github.io/jekyll-theme-yat/
[jekyll-spaceship]: https://github.com/jeffreytse/jekyll-spaceship
[jekyll-seo-tag]: https://github.com/jekyll/jekyll-seo-tag
[jekyll-sitemap]: https://github.com/jekyll/jekyll-sitemap
[jekyll-feed]: https://github.com/jekyll/jekyll-feed
[highlight-js]: https://github.com/highlightjs/highlight.js
[photoswipe-5]: https://photoswipe.com/
