[English](https://github.com/opentiny/tiny-engine/blob/develop/.github/PULL_REQUEST_TEMPLATE.md) | 简体中文

# PR

## PR Checklist

请检查您的 PR 是否满足以下要求：

- [ ] commit message遵循我们的[提交贡献指南](https://github.com/opentiny/tiny-engine/blob/develop/CONTRIBUTING.md)
- [ ] 添加了更改内容的测试用例（用于bugfix/功能）
- [ ] 文档已添加/更新（用于bugfix/功能）
- [ ] 是否构建了自己的设计器，经过了充分的自验证

## PR 类型

这个PR的类型是？

- [ ] 日常 bug 修复
- [ ] 新特性支持
- [ ] 代码风格优化
- [ ] 重构
- [ ] 构建优化
- [ ] 测试用例
- [ ] 文档更新
- [ ] 分支合并
- [ ] 其他改动（请补充）


## 需求背景和解决方案

1. 问题

- 对话不能正常进行，提出问题不能显示回复
- 回复内容没有进行markdown格式转换
- 缺少语音录入功能

2. 新增特性，需要进行功能描述，并附上效果图。
   
  本次pr修复了AI对话功能。
  - 新增填写accesstoken的弹窗，若accesstoken过期则用户需重新填写方可正常对话
  - 新增markdown转换，使其对话内容返回符合markdown格式
  - 新增语音录入功能，能够通过语音转文字然后进行交流

Issue Number: N/A

### 修改前


### 修改后

1.新增弹窗

<img width="1512" alt="image" src="https://github.com/user-attachments/assets/a1d9f532-6d55-42aa-abfe-7ab7b9d676e9">

<img width="1512" alt="image" src="https://github.com/user-attachments/assets/41c2d3a9-fe62-4e51-9862-b604d41c0901">

2.对话修复
<img width="765" alt="image" src="https://github.com/user-attachments/assets/5d0f76d9-ae66-4b8c-9792-256ce6c37a7c">

3.语音转文字
<img width="759" alt="image" src="https://github.com/user-attachments/assets/0e566c94-2944-4586-b9d1-48bc7037d97f">


## 此PR是否含有 breaking change?

- [ ] 是
- [ ] 否

<!-- 如果此 PR 包含breaking change，请在下面从用户角度描述具体变化和其他风险。-->

## Other information
