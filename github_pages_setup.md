# GitHub Pages 部署指南

## 🚀 快速部署步骤

### **步骤1: 创建GitHub仓库**
1. 访问 https://github.com/new
2. 填写仓库信息:
   - **Repository name**: `cryptoai-assistant`
   - **Description**: `Educational cryptocurrency content assistant for TikTok`
   - **Public** (不要选择Private)
   - 不要初始化README (我们会直接上传文件)
3. 点击 "Create repository"

### **步骤2: 上传文件**
有三种方法上传文件:

#### **方法A: Web界面上传 (最简单)**
```
1. 在新建的仓库页面，点击 "Add file" → "Upload files"
2. 将本文件夹所有文件拖放到上传区域
3. 填写提交信息: "Initial commit: TikTok app submission files"
4. 点击 "Commit changes"
```

#### **方法B: Git命令行**
```bash
# 1. 初始化本地仓库
cd /home/x/.openclaw/workspace/tiktok_app_submission
git init
git add .
git commit -m "Initial commit: TikTok app submission files"

# 2. 连接到GitHub仓库
git remote add origin https://github.com/YOUR-USERNAME/cryptoai-assistant.git
git branch -M main
git push -u origin main
```

#### **方法C: GitHub Desktop**
1. 下载GitHub Desktop
2. 克隆仓库到本地
3. 复制本文件夹内容到仓库目录
4. 提交并推送

### **步骤3: 启用GitHub Pages**
```
1. 在仓库页面，点击 "Settings" → "Pages"
2. 在 "Source" 部分:
   - 选择 "Deploy from a branch"
   - 分支: `main`
   - 文件夹: `/` (根目录)
3. 点击 "Save"
4. 等待1-2分钟，刷新页面查看部署URL
```

### **步骤4: 获取访问链接**
部署成功后，你将获得:
```
主URL: https://YOUR-USERNAME.github.io/cryptoai-assistant/
服务条款: https://YOUR-USERNAME.github.io/cryptoai-assistant/terms_of_service.html
隐私政策: https://YOUR-USERNAME.github.io/cryptoai-assistant/privacy_policy.html
```

---

## 🔧 自定义设置

### **自定义域名 (可选)**
如果你有自己的域名:
```
1. 在GitHub Pages设置中添加自定义域名
2. 在域名注册商处设置CNAME记录:
   - 类型: CNAME
   - 主机: www (或 @ 根域名)
   - 值: YOUR-USERNAME.github.io
3. 等待DNS传播 (通常几分钟到几小时)
```

### **更新文件**
当需要更新文件时:
```
1. 在GitHub仓库页面编辑文件
2. 或使用Git命令更新:
   git add .
   git commit -m "Update files"
   git push
3. GitHub Pages会自动重新部署 (约1分钟)
```

---

## 📁 文件结构

部署后的文件结构:
```
https://YOUR-USERNAME.github.io/cryptoai-assistant/
├── README.md
├── form_fields.md
├── app_review_text.txt
├── terms_of_service.html          ← 服务条款
├── privacy_policy.html            ← 隐私政策
├── demo_video_script.md
├── github_pages_setup.md
└── submission_checklist.md
```

### **重要文件URL**
```
服务条款: https://YOUR-USERNAME.github.io/cryptoai-assistant/terms_of_service.html
隐私政策: https://YOUR-USERNAME.github.io/cryptoai-assistant/privacy_policy.html
```

---

## ⚠️ 常见问题

### **Q1: 页面无法访问**
```
可能原因:
1. 仓库不是Public (必须是Public)
2. GitHub Pages未启用 (检查Settings → Pages)
3. 文件不在根目录 (确保文件在仓库根目录)
4. 需要等待部署完成 (通常1-2分钟)

解决方案:
1. 确保仓库设置为Public
2. 重新启用GitHub Pages
3. 检查文件路径
4. 等待后刷新页面
```

### **Q2: 链接返回404**
```
可能原因:
1. 文件名错误 (检查大小写和扩展名)
2. 文件未上传成功
3. GitHub Pages缓存

解决方案:
1. 检查文件名是否正确
2. 重新上传文件
3. 清除浏览器缓存或等待几分钟
```

### **Q3: 自定义域名不工作**
```
可能原因:
1. DNS设置错误
2. GitHub未验证域名
3. HTTPS证书问题

解决方案:
1. 检查DNS设置是否正确
2. 在GitHub Pages设置中重新添加域名
3. 等待HTTPS证书自动签发 (最多24小时)
```

### **Q4: 文件更新后未生效**
```
可能原因:
1. GitHub Pages部署延迟
2. 浏览器缓存

解决方案:
1. 等待1-2分钟
2. 清除浏览器缓存
3. 使用无痕模式访问
```

---

## 🛡️ 安全性考虑

### **公开信息**
GitHub Pages是公开的，请注意:
```
✅ 可以公开的内容:
   - 服务条款和隐私政策 (必须公开)
   - 应用描述文档
   - 演示脚本

❌ 不应公开的内容:
   - API密钥或敏感凭据
   - 个人信息
   - 内部系统细节
```

### **备份建议**
```
1. 本地保留文件副本
2. 定期提交更新到GitHub
3. 考虑使用私有分支存储敏感信息
```

---

## 📊 验证部署

### **验证步骤**
```
1. 访问主URL，确认页面加载
2. 点击服务条款链接，确认可访问
3. 点击隐私政策链接，确认可访问
4. 检查所有链接是否正常工作
5. 在不同设备上测试响应式设计
```

### **验证命令 (可选)**
```bash
# 使用curl验证可访问性
curl -I https://YOUR-USERNAME.github.io/cryptoai-assistant/terms_of_service.html
# 应返回HTTP 200状态码
```

---

## 🎯 TikTok表单填写

当填写TikTok开发者表单时，使用以下URL:

```
Terms of Service URL:
https://YOUR-USERNAME.github.io/cryptoai-assistant/terms_of_service.html

Privacy Policy URL:
https://YOUR-USERNAME.github.io/cryptoai-assistant/privacy_policy.html
```

### **临时方案**
如果尚未部署到GitHub Pages，可以使用:
```
临时服务条款: https://gist.githubusercontent.com/YOUR-USERNAME/.../terms.html
临时隐私政策: https://gist.githubusercontent.com/YOUR-USERNAME/.../privacy.html
```

### **最终方案**
建议使用GitHub Pages，因为:
1. **稳定性**: GitHub提供99.9%可用性
2. **免费**: 完全免费使用
3. **HTTPS**: 自动提供SSL证书
4. **易于更新**: 只需推送更新即可

---

## 🔄 更新流程

### **更新文件**
```
1. 编辑本地文件
2. 提交到GitHub:
   git add .
   git commit -m "Update [文件名]"
   git push
3. 等待GitHub Pages自动部署
```

### **更新TikTok表单**
如果更新了服务条款或隐私政策:
```
1. 更新GitHub上的文件
2. 在TikTok开发者门户更新URL (如果需要)
3. 不需要重新提交审核，除非重大更改
```

---

## 📞 技术支持

### **GitHub帮助**
- GitHub Pages文档: https://docs.github.com/en/pages
- 故障排除: https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting
- 社区论坛: https://github.community/

### **部署状态检查**
1. 仓库 → Actions → 查看Pages部署状态
2. 访问 https://YOUR-USERNAME.github.io/cryptoai-assistant/ 确认可访问
3. 使用在线工具检查HTTPS证书

**记住**: 稳定的URL对于TikTok审核至关重要！