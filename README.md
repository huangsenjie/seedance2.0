# Seedance 2.0 - AI 提示词生成器

基于 Anthropic 长运行代理模式的专业 AI 提示词生成工具。

## 特性

- 📋 生成 Initializer Agent 和 Coding Agent 提示词
- 🎯 基于模板的快速配置（Web应用、API、CLI、数据处理）
- ⚙️ 高级配置选项（测试、文档、Git、CI/CD等）
- 📦 多种导出格式（JSON、Markdown、单独文件）
- 🌙 深色/亮色主题
- 📱 响应式设计，支持移动端
- 🚀 纯静态文件，部署简单

## 在线访问

本项目已部署到 Vercel: https://seedance2.vercel.app

## 本地运行

直接用浏览器打开 `index.html` 即可使用。

或使用静态服务器：

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# 访问
open http://localhost:8000
```

## 使用方法

1. 选择或配置项目参数
2. 点击"生成提示词"
3. 查看生成的提示词
4. 复制或导出为文件

## 参考资源

- [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
- [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts)
