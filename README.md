# Biaobei-French-legal

「手表背法语」（标背法语版）的隐私政策、使用条款与支持页面，通过 GitHub Pages 发布。

## 在线地址

部署完成后访问：

- 首页：https://ykk00.github.io/Biaobei-French-legal/
- 隐私政策：https://ykk00.github.io/Biaobei-French-legal/privacy-policy.html
- 使用条款：https://ykk00.github.io/Biaobei-French-legal/terms-of-use.html

## 新建并发布（首次）

### 1. 在 GitHub 创建仓库

1. 打开 https://github.com/new
2. Repository name 填：`Biaobei-French-legal`
3. 选择 **Public**（GitHub Pages 免费托管需要公开仓库，或使用 GitHub Pro 的私有 Pages）
4. **不要**勾选 “Add a README file”（本地已有文件）
5. 点击 **Create repository**

### 2. 推送本地文件

在本目录执行（将 `YKK00` 换成你的 GitHub 用户名）：

```bash
cd /Users/holden/Developer/Biaobei-French-legal
git init
git add .
git commit -m "Add privacy policy and terms for Biaobei French"
git branch -M main
git remote add origin https://github.com/YKK00/Biaobei-French-legal.git
git push -u origin main
```

### 3. 开启 GitHub Pages

1. 打开仓库 → **Settings** → 左侧 **Pages**
2. **Build and deployment** → Source 选 **Deploy from a branch**
3. Branch 选 `main`，文件夹选 **`/ (root)`**
4. 点击 **Save**
5. 等待 1～3 分钟，页面顶部会显示站点 URL

### 4. 在 App Store Connect 填写

在 App 信息 → **隐私政策 URL** 填入：

`https://ykk00.github.io/Biaobei-French-legal/privacy-policy.html`

应用内订阅页链接已指向上述地址（见 `Biaobei-French` 工程）。

## 更新政策

修改 `privacy-policy.html` 后：

```bash
git add privacy-policy.html
git commit -m "Update privacy policy"
git push
```

Pages 会自动重新部署，通常几分钟内生效。
