# LI Xiao 个人学术主页

这是一个基于 Academic Pages 主题的个人学术网站。网站使用 Jekyll 构建，托管在 GitHub Pages 上。

## 网站信息

- 网站名称：LI Xiao Webpage
- 网站地址：https://xiaoli-cn.github.io
- 主题：Academic Pages (基于 Minimal Mistakes Jekyll 主题)
- 版本：0.8.1.1

## 功能特点

- 响应式设计，支持移动端访问
- 支持学术内容展示（论文、讲座、教学等）
- 支持 Markdown 写作
- 支持评论系统（可选）
- 支持多种社交媒体链接
- 支持 RSS 订阅

## 本地开发

### 环境要求

- Ruby 和 Bundler
- Node.js
- Jekyll

### macOS 安装步骤

```bash
# 安装依赖
brew install ruby
brew install node
gem install bundler

# 安装项目依赖
bundle install
npm install

# 本地运行
jekyll serve -l -H localhost
```

网站将在 `http://localhost:4000` 运行。

## Docker 部署

如果您不想安装本地依赖，可以使用 Docker 运行网站：

```bash
docker compose up
```

同样可以通过 `http://localhost:4000` 访问网站。

## 目录结构

- `_config.yml`: 网站配置文件
- `_pages/`: 网站页面
- `_posts/`: 博客文章
- `_publications/`: 发表的论文
- `_talks/`: 学术报告
- `_teaching/`: 教学材料
- `assets/`: 网站资源文件
- `files/`: 可下载文件
- `images/`: 图片资源

## 许可证

本项目基于 MIT 许可证开源。

## 致谢

- 基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 主题开发
- 原主题由 [Stuart Geiger](https://github.com/staeiou) 开发
- 基于 [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) 修改
