# git

## git学习资料

[Git 的奇技淫巧](https://github.com/521xueweihan/git-tips)

[ 如何写好一个git提交](https://zhuanlan.zhihu.com/p/27501055)

知乎搜到的一种民间格式

`[任务分类] 主要修改组件（可选）：修改内容`

开源格式
`<type>(<scope>): <subject><BLANK LINE><body><BLANK LINE><footer>`
诸如： docs(changelog): update change log to beta.5 中：
- docs(changelog): update change log to beta.5 中：

- docs 则对应修改的类型
- changelog 则是影响的范围
- subject 则是对应做的事件

对应的类型有：

- build: 影响构建系统或外部依赖关系的更改（示例范围：gulp，broccoli，npm）
- ci: 更改我们的持续集成文件和脚本（示例范围：Travis，Circle，BrowserStack，SauceLabs）
- docs: 仅文档更改
- feat: 一个新功能
- fix: 修复错误
- perf: 改进性能的代码更改
- refactor: 代码更改，既不修复错误也不添加功能
- style: 不影响代码含义的变化（空白，格式化，缺少分号等）
- test: 添加缺失测试或更正现有测试


新建github仓库 未创建远程分支
- 新建分支并绑定远程分支

`git push -u origin master`