# Vercel 部署指南

由于 Vercel CLI 遇到问题，请使用 Vercel 网页界面进行部署。

## 方法 1: 使用 Vercel 网页界面（推荐）

### 步骤：

1. 访问 Vercel 部署页面：
   ```
   https://vercel.com/new
   ```

2. 点击 "Import Project"

3. 选择 "Git" 选项，然后搜索或输入你的仓库：
   ```
   huangsenjie/seedance2.0
   ```

4. 点击 "Import" 按钮

5. 配置部署设置：
   - **Project Name**: `seedance2-0` (自动填充)
   - **Framework Preset**: 选择 `Other` 或 `None`
   - **Root Directory**: 留空或输入 `./`
   - **Build Command**: 留空
   - **Output Directory**: 留空（默认是 `.`）

6. 点击 "Deploy" 按钮

7. 等待部署完成（通常需要 30-60 秒）

8. 部署成功后，你会获得一个 URL，例如：
   ```
   https://seedance2-0-xxxxx.vercel.app
   ```

## 方法 2: 使用 Vercel CLI（修复后）

如果 CLI 问题解决后，可以尝试：

```bash
# 1. 全局安装 Vercel CLI
npm i -g vercel

# 2. 登录 Vercel
vercel login

# 3. 部署
cd D:/AI-project/seedance2.0
vercel --prod
```

## 部署后

部署成功后，可以通过以下方式访问：

- **访问地址**: Vercel 提供的 URL（如 https://seedance2-0.vercel.app）
- **GitHub**: https://github.com/huangsenjie/seedance2.0
- **Vercel Dashboard**: https://vercel.com/dashboard

## 当前状态

- ✅ GitHub 仓库: https://github.com/huangsenjie/seedance2.0
- ✅ 代码已推送
- ⏳ 等待 Vercel 部署
