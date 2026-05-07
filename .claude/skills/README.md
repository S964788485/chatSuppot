# Skills 文件夹结构说明

## 目录结构
```
.claude/
└── skills/
    ├── template-skill/
    │   └── SKILL.md
    └── your-skill-name/
        └── SKILL.md
```

## SKILL.md 文件格式

每个技能必须包含 `SKILL.md` 文件，格式如下：

```markdown
---
name: skill-name          # 技能名称（必须，调用时使用）
description: 简短描述      # 技能描述（必须）
---

# 技能内容

这里编写具体的指令和规范，可以包含：
- 任务说明
- 执行步骤
- 代码规范
- 注意事项
- 模板变量：{{变量名}}
```

## 使用方式

1. 创建新技能：复制 `template-skill` 文件夹
2. 重命名为你的技能名称
3. 编辑 `SKILL.md` 中的内容和 frontmatter
4. 通过 `/skill-name` 或 Skill 工具调用

## 技能命名规范

- 使用小写字母
- 使用连字符分隔单词
- 例如：`add-feature`、`code-review`、`build-service`
