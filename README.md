# Seyo汐游创新

## 📖 项目介绍

**Seyo汐游创新**是一个来自重庆大学的学生创新团队。我们从一次偶然的接触**潜水**这项运动后，便决定专注于降低水下运动的参与门槛，致力于让更多人能够发掘水的魅力、体验潜水的乐趣。

我们相信通过创新和技术，可以让每个热爱水的人都有机会安全地探索水下世界。

## 🌐 Web项目

该仓库为汐游创新早期Web界面搭建，记录产品从0到1的研发过程。

**在线访问**: [Seyo汐游创新官网](https://www.seyoinnovation.cn)

## 📋 项目结构

```
web_Seyo/
├── source/              # 源文件目录
│   ├── _posts/          # 博客文章
│   ├── about/           # 关于页面
│   ├── news/            # 新闻页面
│   ├── products/        # 产品页面
│   ├── Team/            # 团队页面
│   └── images/          # 资源图片
├── public/              # 生成的静态网站
│   ├── css/             # 样式文件
│   ├── js/              # JavaScript文件
│   ├── fancybox/        # 图片库插件
│   └── images/          # 发布的图片资源
├── themes/              # 主题目录
│   └── Hiker/           # Hiker主题
├── scaffolds/           # 文章模板
├── package.json         # 项目依赖配置
├── _config.yml          # Hexo主配置文件
└── README.md            # 本文件
```

## 🚀 快速开始

### 前置要求

- Node.js (v12.0.0 或更高)
- npm 或 yarn

### 安装依赖

```bash
npm install
```

### 本地开发

```bash
# 启动开发服务器
hexo server

# 或使用简写
hexo s
hexo s -p [port]
```

访问 `http://localhost:4000` 预览网站

### 生成静态文件

```bash
# 清空并生成静态文件
hexo clean && hexo generate

# 或使用简写
hexo clean && hexo g
```

### 部署

```bash
# 部署到配置的服务器
hexo deploy

# 或使用简写
hexo d
```

## 📝 常用命令

| 命令 | 说明 |
|------|------|
| `hexo new [layout] <title>` | 创建新文章 |
| `hexo server` | 启动本地服务器 |
| `hexo generate` | 生成静态文件 |
| `hexo deploy` | 部署到服务器 |
| `hexo clean` | 清空缓存和public目录 |

## 🎨 主题配置

当前使用 **Hiker** 主题，主题配置文件位于:
- `themes/Hiker/_config.yml` - 主题配置
- `themes/Hiker/languages/` - 多语言支持

## 📦 主要依赖

- **hexo** - 静态网站生成器
- **hexo-deployer-git** - Git部署插件
- **jquery** - JavaScript库
- **fancybox** - 图片灯箱效果

## 🤝 加入我们

### 🏊 潜水爱好者

如果你是潜水爱好者或对水下运动充满热情，我们真诚地欢迎你与我们交流！你可以：
- 分享你的潜水经历和建议
- 体验我们的产品和服务
- 参与我们的社区讨论和活动

### 💰 天使用户/投资者

我们诚邀志同道合的**天使用户**加入我们的团队：
- 成为我们的早期支持者和体验者
- 获得独家的产品体验和优惠
- 与我们共同打造水运动生态
- 参与决策和产品开发方向

### 👨‍💻 开发者贡献

欢迎提交Issue和Pull Request来改进项目！


## 📞 联系我们

无论你是潜水爱好者、投资者还是开发者，我们都期待与你沟通！

- 🎓 **学校**: 重庆大学
- 📧 **Email**: wangzinuo233@gmail.com
- 🌐 **官网**: [Seyo汐游创新](https://www.seyoinnovation.cn)
- 💬 **微信**: 欢迎扫描官网二维码联系我们

**一起潜水，一起创新！**

---

**最后更新**: 2026年1月27日