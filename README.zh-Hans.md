<div align="center">
  <h1>lailai0916 · GitHub 默认配置</h1>
  <p><a href="README.md">English</a> | 简体中文</p>
  <p>
    <img src="https://img.shields.io/github/last-commit/lailai0916/.github?style=flat-square" alt="最后提交" />
    <img src="https://img.shields.io/github/license/lailai0916/.github?style=flat-square" alt="许可证" />
  </p>
</div>

## 项目简介

`lailai0916` 名下仓库的社区健康文件单一真源。未提供本地覆盖的仓库会从这里继承
issue 模板、PR 清单、贡献指南与安全策略。

## 项目特性

📮 **Issue 收集** —— 双语模板分别收集 bug 与功能建议，并要求提供复现信息。

🔀 **审查基线** —— PR 清单统一检查范围、验证、文档与 Agent 指引。

🧭 **贡献指南** —— 若仓库未提供项目专属说明，则使用共享工作流与提交规范。

🔒 **安全策略** —— 安全漏洞通过 GitHub 私密报告渠道提交，不在公开 issue 中披露。

## 快速开始

GitHub 会自动将这些文件应用到没有同类本地文件的仓库。仓库可通过添加本地文件覆盖
默认值。若某仓库的 `.github/ISSUE_TEMPLATE/` 中存在任意文件，则会整体覆盖继承的
issue 模板目录。

`lailai-template` 为了支持在该账号外创建仓库，会有意保留一份可移植模板。其他仓库仅应
保留项目专属覆盖。

## 项目结构

```bash
.github/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md           # 共享 bug 报告
│   │   ├── config.yml              # issue 创建设置
│   │   └── feature_request.md      # 共享功能建议
│   ├── CONTRIBUTING.md             # 贡献工作流
│   ├── PULL_REQUEST_TEMPLATE.md    # PR 清单
│   └── SECURITY.md                 # 私密漏洞报告策略
├── .gitignore                      # 忽略的本地文件
├── LICENSE                         # 代码许可协议
├── README.md                       # 英文文档
└── README.zh-Hans.md               # 简体中文文档
```

## 许可协议

本项目代码采用 [MIT 许可协议](LICENSE)。
