# Seedance 2.0 - Vercel 部署指南

## 推荐方法：Vercel 网页界面（最简单）

### 步骤 1：访问 Vercel

1. 打开浏览器访问：**https://vercel.com/new**

### 步骤 2：导入 GitHub 仓库

2. 在页面中：
   - 确认在 "Git" 标签下
   - 在搜索框输入：`huangsenjie/seedance2.0`
   - 或点击 GitHub 图标，从你的仓库列表中选择 `seedance2.0`

3. 点击 **"Import"** 按钮

### 步骤 3：配置项目设置

Vercel 会自动检测项目类型，但请确认以下设置：

| 设置项 | 推荐值 |
|--------|----------|
| **Project Name** | `seedance2-0`（会自动填充） |
| **Framework Preset** | `Other` 或 `None` |
| **Root Directory** | 留空或输入 `./` |
| **Build Command** | 留空 |
| **Output Directory** | `.` 或留空 |

这些设置已经优化为静态 HTML 站点。

### 步骤 4：部署

4. 点击底部的 **"Deploy"** 按钮

5. 等待 30-60 秒，你会看到部署进度条

### 步骤 5：完成

6. 部署成功后，你会得到：
   ```
   https://seedance2-0-xxxxxxxx.vercel.app
   ```

7. 点击 "Visit" 按钮访问你的网站

---

## 备用方案：GitHub Pages

如果 Vercel 有问题，可以使用 GitHub Pages：

### 步骤：

1. 访问：https://github.com/huangsenjie/seedance2.0/settings/pages

2. 在 "Source" 下选择：
   - **Branch**: `main`
   - **Folder**: `/ (root)`

3. 点击 **Save**

4. 等待 1-2 分钟

5. 访问：https://huangsenjie.github.io/seedance2.0/

---

## 当前状态

- ✅ GitHub 仓库: https://github.com/huangsenjie/seedance2.0
- ✅ 代码已推送
- ⏳ 等待 Vercel 网页部署

---

## CLI 部署遇到的问题

尝试的 CLI 部署方法遇到了以下错误：

**Vercel CLI**: `TypeError: (intermediate value).ProxyAgent is not a constructor`
- 这是一个已知的 Vercel CLI 50.17.0 版本问题
- 建议使用网页界面而非 CLI

因此，**推荐使用 Vercel 网页界面**进行部署。
