# 🤝 Contributing Guide

感谢你有兴趣为本项目贡献！请遵循以下规范以保持代码质量和协作高效。

## 🧩 分支命名规范
- 功能分支：`feature/<name>`  
- 修复分支：`fix/<name>`  
- 文档分支：`docs/<name>`  
- 临时实验：`test/<name>`  

示例：  
```
git checkout -b feature/add-multi-token-support
```

## 💬 提交规范
请使用简洁的英文提交信息：  
- `feat: add deposit function`  
- `fix: resolve balance overflow issue`  
- `docs: update README`  

## 🔀 提交 Pull Request
1. 确保从 `main` 分支创建分支  
2. 推送到远程仓库后发起 PR  
3. 填写 PR 模板说明变更内容  
4. 等待代码评审（@konck2star-eng 或其他成员）  
5. 合并后删除分支

## 🧹 代码风格
- Solidity：遵守 [Solidity Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
- JS/TS：遵守 ESLint + Prettier 格式化规范

## ⚙️ 测试
请在提交前运行测试：  
```
npx hardhat test
```

## 🛡️ 安全报告
发现漏洞请通过私信或邮件联系项目维护者，不要公开在 Issue 中发布。

---
维护者：@konck2star-eng  
署名：47
