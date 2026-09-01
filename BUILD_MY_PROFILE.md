# AI 一键生成提示词

在当前仓库中打开 Codex 或其他能编辑文件的 AI 编程助手，把下面整段提示词复制给它：

```text
请根据当前仓库里的资料，为我生成 GitHub 个人主页。

1. 完整读取 PROFILE_INFO.md，并把它作为我个人信息的唯一真实来源。
2. 读取 README.template.md，沿用其中紧凑的模块顺序和版式。
3. 用生成后的个人主页覆盖根目录 README.md。About Me 必须排在第一位，并且只保留一句英文介绍。
4. 使用 PROFILE_INFO.md 的内容替换个人主页 README 中的全部 {{PLACEHOLDER}}。
5. 修改 x-card.svg 中的显示名称、X 用户名、名片顶部文字、主色和辅助色。保持名片内部排版以及 3:1 长宽比例不变。
6. 只有产品名称、链接和介绍都填写完整时，才把它加入 My Products；删除未填写产品对应的整行，不要留下空行。
7. 不要编造个人资料、网址、用户名或产品介绍。如果缺少必要信息，先停止并向我询问。
8. 保留 PROFILE_INFO.md、QUICK_START.md、BUILD_MY_PROFILE.md、README.template.md 和 LICENSE，方便我以后重复使用。
9. 不要修改仓库公开状态、设置、分支或其他无关文件。
10. 完成前逐项检查：
   - 邮箱链接使用 mailto:
   - X 名片点击后打开我的 X 主页
   - 小红书链接正确
   - 所有产品仓库链接正确
   - README.md 和 x-card.svg 中不再存在 {{PLACEHOLDER}}
   - My Products 表格能正常显示

编辑前先给我一份简短的变更摘要，等我确认后再修改。完成后告诉我具体改了哪些文件。
```
