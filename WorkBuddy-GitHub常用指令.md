```
# WorkBuddy 对接 GitHub 常用指令集
> 仓库示例名：`test-workbuddy`，使用时可替换为你的仓库名称
> 前提：已完成WorkBuddy GitHub连接器授权
> 权限提示：只读权限可执行查询、读取类指令；写内容、提交代码类需要开启读写授权

## 一、仓库基础信息查询
1. 列出仓库全部文件和目录结构
```

列出 test-workbuddy 仓库的全部文件和目录结构

```
2. 获取最近代码提交记录
```

获取 test-workbuddy 仓库最近 5 条代码提交记录，每条简要说明改动内容

```
3. 指定分支查询（示例main分支）
```

读取 test-workbuddy main 分支的 README 内容

```

## 二、仓库文件&文档读取
1. 读取指定文件并解释内容
```

读取 test-workbuddy 仓库里 xxx.py 文件内容，并简单解释代码作用

```
2. 批量检索仓库内md文档
```

遍历 test-workbuddy 仓库，找出所有 md 文档，列出文档标题

```
3. 读取README并总结（本次已测试成功）
```

读取 test-workbuddy 仓库里的 README.md，把内容总结给我

```

## 三、Issues 任务相关
1. 查询未关闭的Issues并汇总
```

列出 test-workbuddy 仓库所有 open 状态的 issues，汇总需求

```
2. 分析单个issue
```

读取 test-workbuddy 仓库编号 #2 的 issue，分析问题描述并给出解决方案

```

## 四、PR 代码评审相关
1. 最新PR代码评审
```

查看 test-workbuddy 仓库最新一条 PR，帮我做代码评审，指出潜在风险

```
2. 对比PR改动内容
```

查看 test-workbuddy 最新 PR 的代码改动，总结变更点

```

## 五、生成文档文本（需读写权限）
1. 生成版本发布日志 Release Notes
```

根据 test-workbuddy 最近的提交记录，生成一份简洁的 Release Notes

```
2. 更新README文档，新增章节
```

为 test-workbuddy 仓库更新 README，新增一个【快速上手】章节

```
3. 生成规范Git提交备注
```

帮我写 3 条规范简洁的 git commit 提交信息，用于 test-workbuddy 仓库

```

## 六、代码分析辅助
1. 梳理项目架构
```

读取 test-workbuddy 仓库的代码，梳理项目整体架构，输出文字版架构图

```
2. 代码查找BUG与优化建议
```

查找 test-workbuddy 仓库代码里的 BUG 和可优化点，给出修改建议

```

## 七、安全相关说明
1. 日常查看仓库信息，使用**只读权限**即可，安全性更高
2. 写文件、创建PR、提交代码，才需要开启读写授权
3. 撤销授权：GitHub头像 → Settings → Applications → Authorized OAuth Apps → WorkBuddy → Revoke
```
新增 WorkBuddy 指令清单文档 
