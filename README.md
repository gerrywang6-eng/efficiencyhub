# EfficiencyHub - OpenClaw与AI Bot专家

OpenClaw完全指南 | Bot租赁市场分析 | AI自动化变现方法

## 网站信息

- **主题**: Hugo PaperMod
- **构建工具**: Hugo v0.155.3
- **部署**: GitHub Pages + GitHub Actions
- **自动化**: Push即自动发布

## 本地开发

```bash
# 启动本地服务器
hugo server -D

# 创建新文章
hugo new posts/article-name.md

# 构建网站
hugo

# 部署到GitHub Pages（自动）
git add .
git commit -m "Add new article"
git push
```

## 文章发布流程

1. 创建Markdown文件到 `content/posts/` 目录
2. 添加Front Matter（标题、日期、标签等）
3. 编写内容
4. Git push
5. GitHub Actions自动构建并发布

## 目录结构

```
efficiencyhub/
├── content/
│   └── posts/          # 文章目录
├── static/             # 静态文件
├── themes/
│   └── PaperMod/       # 主题
├── .github/
│   └── workflows/
│       └── hugo.yaml   # 自动发布配置
└── hugo.yaml           # 网站配置
```

## 网站特性

- ✅ 响应式设计
- ✅ SEO优化
- ✅ 代码高亮
- ✅ 搜索功能
- ✅ 标签和分类
- ✅ RSS订阅
- ✅ 阅读时间显示
- ✅ 目录导航
- ✅ 深色模式切换

## 下一步

1. 创建GitHub仓库
2. 推送代码到GitHub
3. 启用GitHub Pages
4. 自动发布完成！
