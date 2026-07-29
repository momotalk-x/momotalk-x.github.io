# Momotalk-X

## 软件介绍页面

### 📄 文件说明

- `index.html` - 主页（白色背景，图标 + 两个按钮）
- `icon.png` - 工作区图标

### 🔧 如何上传到 GitHub Pages

1. **确保本地已完成所有修改并提交**
   ```bash
   git status
   git add index.html icon.png README.md
   git commit -m "Add software intro page"
   ```

2. **推送代码到远程仓库**
   
   **方法 A：使用 HTTPS + Personal Access Token**
   ```bash
   # 生成 GitHub Personal Access Token (设置 scope: repo)
   git remote set-url origin https://<YOUR_TOKEN>@github.com/momotalk-x/momotalk-x.github.io.git
   git push -u origin main
   ```

   **方法 B：使用 SSH（推荐）**
   ```bash
   # 配置 SSH 密钥 (如果还没有的话)
   ssh-keygen -t ed25519 -C "your-email@example.com"
   
   # 添加 SSH 公钥到 GitHub
   # 然后推送
   git remote set-url origin git@github.com:omotalk-x/momotalk-x.github.io.git
   git push -u origin main
   ```

3. **在 GitHub Settings 中配置 Pages**
   - 进入仓库 Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch: `main` (或 master)
   - 保存后约 1-2 分钟即可访问你的网站：https://omotalk-x.github.io/momotalk-x/

### 🎨 页面预览

- **顶部**：居中的工作区 icon.png（120x120px）
- **两个按钮**（白色背景，极简风格）
  - "下载软件" - 紫色渐变按钮
  - "了解软件" - 粉色渐变按钮

---

*Last Updated: 2026/07/29*
