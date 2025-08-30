# 🤝 Contributing to AI X

感谢你对 **AI X — 100 个职业的 AI 使用手册** 项目的关注与支持！  
这是一个面向社区的开源协作项目，我们希望通过大家的力量，整理出 **100+ 职业的 AI 使用指南**，让更多人受益。

---

## 📌 如何参与

### 1. Fork & Clone
1. 点击右上角 **Fork**，将仓库复制到你的 GitHub 账户。  
2. 克隆到本地：
   ```bash
   git clone https://github.com/<your-username>/AI-X.git
   cd AI-X
   ```

### 2. 新建分支
```bash
git checkout -b add-new-role
```

### 3. 新建角色文档
- 所有角色文件放在 `roles/` 目录下。  
- 命名规则：`角色英文名.md`，例如：
  - `media-creator.md`
  - `doctor.md`
  - `finance.md`

### 4. 按模板撰写内容
请参考 **roles-template.md**，至少包含以下板块：
- 简介 & 核心目标  
- 常用 AI 工具推荐  
- 核心流程  
- 高频 Prompt 模板  
- 实用案例  
- 进阶玩法  
- 常见坑 & 应急方案  
- 延伸资源  

### 5. 提交修改
```bash
git add .
git commit -m "add: 新增角色 role-name"
git push origin add-new-role
```

### 6. 提交 Pull Request
- 在 GitHub 页面创建 **Pull Request**。  
- Maintainers 会在合并前进行审核。  

---

## 🧩 共创原则
- **保持一致性**：内容结构需与 `roles-template.md` 保持统一。  
- **注重实用性**：避免空洞描述，提供工具、Prompt、案例。  
- **学术 & 专业伦理**：禁止虚假数据、杜撰案例。  
- **多语言兼顾**：若能，尽量提供中/英文兼顾的表达。  
