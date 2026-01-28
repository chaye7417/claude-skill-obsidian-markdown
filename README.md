# Obsidian Markdown 编辑器 (Obsidian Markdown)

创建和编辑 Obsidian 风格的 Markdown 文件，支持双链、嵌入、Callout 等特性。

## 功能

- 完整支持 Obsidian 扩展语法
- 双向链接（Wikilinks）
- 文件和块嵌入
- Callout 提示框
- 前置属性（Properties/Frontmatter）
- 标签系统

## Obsidian 特有语法

### 双向链接
```markdown
[[笔记名称]]
[[笔记名称|显示文本]]
[[笔记名称#标题]]
```

### 嵌入
```markdown
![[文件名]]
![[文件名#标题]]
![[文件名#^块ID]]
```

### Callout
```markdown
> [!note] 标题
> 内容

> [!warning]
> 警告内容
```

### 前置属性
```yaml
---
title: 笔记标题
tags: [tag1, tag2]
date: 2024-01-01
---
```

## 使用方法

在 Claude Code 中说：
- "创建一个 Obsidian 笔记"
- "添加双链到这篇笔记"
- "用 Callout 格式化这段提示"

## 依赖

- Obsidian

## 作者

[@chaye7417](https://github.com/chaye7417)

## 许可证

MIT
