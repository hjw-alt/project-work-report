# 项目工作汇报 Skill

根据日报、每周汇报、Git 提交，以及微信等聊天和协作记录，为任意项目生成周报、月报或阶段简报。核心工作使用 ①②③ 连续编号，主要成果注明交付、关键数字和完成阶段。

每张清单表格上方用一句话概括当期关键进展。单项目用「核心工作清单｜主要成果」两列。多项目在首列增加项目或系统名称，每个对象一行。

## 安装到 Codex

从本仓库复制 HTTPS 地址，替换命令中的 `<仓库地址>`。

**Windows（PowerShell）**

```powershell
git clone "<仓库地址>" "$env:USERPROFILE\.agents\skills\project-work-report"
```

**macOS / Linux**

```bash
git clone "<仓库地址>" "$HOME/.agents/skills/project-work-report"
```

也可以在仓库页面选择 **Code → Download ZIP**，解压后把含有 `SKILL.md` 的文件夹命名为 `project-work-report`，放到用户主目录下的 `.agents/skills/`。

## 使用示例

在 Codex 中提供可用的日报、周报、聊天记录或仓库，指定汇报范围和期间。Skill 默认生成横向 A4 的 PDF 文件。需要其他交付格式时，在当次请求中说明。

> 用 $project-work-report 整理知识库改版项目的 4 月工作简报。结合本月日报、每周汇报、当前仓库提交和我发来的消息，按核心工作清单、主要成果两列呈现。

> 用 $project-work-report 把附件里的工作记录整理成 4 月和 5 月项目简报。按月分表，每个项目一行，保留工作序号和主要成果。

参阅 [简洁汇报示例](references/report-example.md) 和 [Git 取数方法](references/git.md)。
