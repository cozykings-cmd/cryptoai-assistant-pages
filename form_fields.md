# TikTok应用表单字段填写指南

## 📝 字段对应表

### **🔑 Credentials (凭据)**
*这些字段TikTok会自动生成，无需填写*

### **🖼️ Basic Information (基本信息)**

#### **1. App icon ***
```
文件: app_icon.png (已提供)
要求: 1024px × 1024px, PNG格式
说明: 抽象的数据可视化图标，蓝色和橙色主题
```

#### **2. App name ***
```
填写: CryptoAI_Assistant
说明: 18/50字符，符合AI+加密货币教育定位
```

#### **3. Category ***
```
选择: Education (首选)
备选: Entertainment (如果Education不可用)
避免: Finance, Business, Investment
理由: 明确教育定位，减少审核风险
```

#### **4. Description ***
```
填写 (英文):
"AI-powered cryptocurrency education assistant. Generates data-driven insights and visualizations to explain blockchain concepts. For entertainment and educational purposes only."

中文翻译:
"AI驱动的加密货币教育助手。生成数据驱动的洞察和可视化来解释区块链概念。仅供娱乐和教育目的。"

字数: 120字符 (刚好)
关键要素: AI、教育、数据驱动、可视化、免责声明
```

#### **5. Terms of Service URL ***
```
填写: https://your-username.github.io/cryptoai-assistant/terms_of_service.html
备用: 使用GitHub Gist链接 (如需)
```

#### **6. Privacy Policy URL ***
```
填写: https://your-username.github.io/cryptoai-assistant/privacy_policy.html
备用: 使用GitHub Gist链接 (如需)
```

#### **7. Platforms ***
```
选择: ✅ Web
选择: ✅ Desktop (可选)
选择: ❌ Android (除非计划开发移动端)
选择: ❌ iOS (除非计划开发移动端)

理由: 内容发布系统基于Web API，不需要移动端
```

### **📋 App Review (应用审核)**

#### **8. Required information for app submission ***
```
完整文本见: app_review_text.txt

核心要点:
1. 应用目的: AI驱动的加密货币教育工具
2. TikTok集成: 使用Content Posting API上传教育视频
3. 使用范围: video.upload, video.publish
4. 工作流程: AI生成 → 合规审查 → API上传 → 用户审核发布
5. 合规保证: 所有内容标注"仅供教育目的，非财务建议"
6. 示例: 生成60秒比特币市场周期教育视频

字数: ~800字符 (留有余地)
```

#### **9. Upload at least one demo video ***
```
文件要求: mp4或mov格式，≤50MB
内容要求: 展示完整端到端集成流程
脚本参考: demo_video_script.md

关键展示点:
1. CryptoAI_Assistant网站界面
2. AI生成教育内容流程
3. TikTok OAuth授权流程
4. Content Posting API调用
5. TikTok收件箱收到上传通知
6. "仅供教育目的"免责声明展示
```

### **🔧 Products (产品)**

#### **10. 选择的产品**
```
必选: ✅ Content Posting API
理由: 用于上传教育视频内容

可选: ❌ 其他API (除非实际需要)
建议: 只选实际需要的产品，减少审核复杂度
```

#### **11. Scopes (权限范围)**
```
必选: ✅ video.upload
必选: ✅ video.publish
理由: 上传和发布教育视频内容

可选: ❌ 其他scope (除非实际需要)
注意: 每个scope必须在演示视频中展示使用
```

---

## 🎯 填写顺序建议

### **第一阶段: 基础信息 (立即填写)**
1. App name: `CryptoAI_Assistant`
2. Category: `Education`
3. Description: 复制提供的文本
4. Platforms: 选择 `Web`

### **第二阶段: 链接准备 (需要部署)**
5. Terms of Service URL: 部署后填写
6. Privacy Policy URL: 部署后填写

### **第三阶段: 审核材料 (需要准备)**
7. App icon: 上传提供的图标文件
8. Demo video: 录制并上传
9. App review: 复制提供的完整文本

### **第四阶段: 产品选择**
10. Products: 选择 `Content Posting API`
11. Scopes: 选择 `video.upload` 和 `video.publish`

---

## ⚠️ 常见错误避免

### **❌ 不要做的**
1. **不要选择金融相关分类**: 避免Finance/Business类别
2. **不要使用敏感词汇**: 避免investment, trading, profit等词
3. **不要申请不需要的权限**: 只选实际需要的scopes
4. **不要使用临时域名**: 确保域名稳定可用
5. **不要省略免责声明**: 所有内容必须包含"仅供教育目的"

### **✅ 必须做的**
1. **必须展示完整流程**: 演示视频要端到端
2. **必须域名匹配**: 视频中网站域名与提供URL一致
3. **必须清晰展示UI**: 视频要清晰展示用户界面
4. **必须包含免责声明**: 所有文案和视频都要有
5. **必须合规描述**: 强调教育目的，非财务建议

---

## 🔍 提交前检查清单

✅ App name符合要求 (18/50字符)
✅ Category选择Education
✅ Description包含免责声明
✅ Terms of Service URL可访问
✅ Privacy Policy URL可访问  
✅ App icon已上传 (1024×1024px)
✅ Demo video已上传 (展示完整流程)
✅ App review文本完整 (~800字符)
✅ Products选择正确 (Content Posting API)
✅ Scopes选择正确 (video.upload, video.publish)
✅ 所有内容强调"教育目的，非财务建议"

---

## 🚀 提交后预期

### **审核时间**
- 首次提交: 3-7个工作日
- 如需修改: 额外2-3个工作日

### **可能的要求**
1. **补充材料**: 可能需要更多说明或截图
2. **修改描述**: 可能需要调整文案强调合规
3. **重新录制视频**: 如果流程展示不清晰

### **成功标志**
1. **审核通过**: 收到批准邮件
2. **获取凭据**: Client Key和Client Secret
3. **开始测试**: 可在沙盒环境测试API

### **后续步骤**
1. 在沙盒环境测试API集成
2. 确保OAuth流程正常工作
3. 开始内容生成和上传测试