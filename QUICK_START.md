# 零基础复刻 GitHub 个人主页

你只需要一个 GitHub 账号和 Codex 等 AI 编程助手，不需要自己写代码。

## 第一步：生成自己的仓库

1. 点击本仓库上方的 **Use this template**。
2. 选择 **Create a new repository**。
3. Owner 选择你自己的 GitHub 账号。
4. Repository name 必须填写你的 GitHub 用户名，大小写也要一致。
5. 选择 **Public**。
6. 点击 **Create repository**。

GitHub 会把“公开且名称与用户名完全相同”的仓库识别为个人主页仓库，其中的 `README.md` 会展示在你的主页。

## 第二步：只填写一份资料

打开 `PROFILE_INFO.md`，点击编辑按钮，把示例内容换成你自己的：

- 一句话英文介绍
- 邮箱
- X 用户名和主页链接
- 小红书名称和主页链接
- 最多 6 个产品或仓库
- 个人紫蓝识别色

没有 6 个产品也没关系，多余的产品模块保持空白即可。

## 第三步：让 AI 自动生成主页

打开 `BUILD_MY_PROFILE.md`，复制里面完整的提示词，发送给能够编辑该仓库的 Codex 或其他 AI 编程助手。

AI 会自动：

1. 读取你的资料表。
2. 根据 `README.template.md` 生成主页 `README.md`。
3. 修改 `x-card.svg` 中的姓名、X 用户名和配色。
4. 删除没有填写的产品行。
5. 检查所有链接和占位符。

先看 AI 给出的变更摘要，确认后再让它提交。

## 第四步：设置 6 个精选项目

进入你的 GitHub 主页：

1. 找到 **Pinned** 区域。
2. 点击 **Customize your pins**。
3. 选择最能代表你的 6 个项目。
4. 把视觉效果最好、最有代表性的项目放在第一位。

## 推荐的主页顺序

1. **About Me**：只写一句话
2. **How to reach me**：邮箱、小红书和小尺寸 X 名片
3. **My Products**：用表格展示产品
4. **Pinned repositories**：使用 GitHub 自带的项目卡片

## 常见问题

### 主页没有显示 README

检查仓库是否为 Public，以及仓库名是否和 GitHub 用户名完全一致。

### X 名片仍然显示大括号占位符

让 AI 检查 `README.md` 和 `x-card.svg`，替换所有 `{{...}}` 内容。

### X 名片太大

把 `README.md` 中的 `width="38%"` 改成 `width="32%"`。不要改变 SVG 内部的长宽比例。

### 产品表格出现空行

删除对应产品的整行 Markdown 表格，不要保留空单元格。

### 修改后仍显示旧图片

等待一分钟再刷新。GitHub 有时会短暂缓存 README 里的图片。
