# 关于我 👋

> 充满鲜花的世界到底在哪里，如果它真的存在那么我一定会去。

[![Blog](https://img.shields.io/badge/Blog-Can%20you%20feel%20my%20world-0f766e?style=flat-square)](https://yudongyouqing.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-yudongyouqing-24292f?style=flat-square&logo=github)](https://github.com/yudongyouqing)
[![Go](https://img.shields.io/badge/Golang-Backend-00ADD8?style=flat-square&logo=go&logoColor=white)](https://go.dev/)

你好，我是 **clearlove13**。

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=0F766E&vCenter=true&width=420&lines=Go+%E5%90%8E%E7%AB%AF%E5%BC%80%E5%8F%91%3B%E5%BA%95%E5%B1%82%E5%8E%9F%E7%90%86%E7%88%B1%E5%A5%BD%E8%80%85%3BACMer%3Blol%E6%B5%B7%E6%96%97%E5%A4%A7%E7%8E%8B)](https://git.io/typing-svg)

Golang 后端开发，技术爱好者。喜欢探究底层实现，也乐于分享开源小工具。


## 开源贡献 🧩

主要在 [EverMind-AI/Raven](https://github.com/EverMind-AI/Raven)（开源多智能体生态系统）：已合并 11 个 PR，集中在子代理 DAG 执行、MCP 客户端正确性、沙箱与升级链路；另有 3x-ui、teamai-cli、AgentRecall 各一个。

| 项目 | 工作 |
| --- | --- |
| Raven [#1264](https://github.com/EverMind-AI/Raven/pull/1264) | Agent Plugin 账本从按包名登记改为按 workspace 隔离（v2 记录），覆盖或删除前校验宿主创建的标记；v1 记录保留为未验证来源，损坏账本拒载，失败的删除可重试。 |
| Raven [#955](https://github.com/EverMind-AI/Raven/pull/955) / [#1002](https://github.com/EverMind-AI/Raven/pull/1002) / [#1056](https://github.com/EverMind-AI/Raven/pull/1056) | 子代理 DAG：DAG 节点改经 `sandbox_factory` 逐节点构建执行器，`tools.sandbox` 配置不再被静默绕过；replan 命中的那一轮为 skipped/cancelled 节点补发终态帧；TUI 对从未运行的节点不再显示 0s 时长。 |
| Raven [#825](https://github.com/EverMind-AI/Raven/pull/825) / [#859](https://github.com/EverMind-AI/Raven/pull/859) | MCP 客户端分页：`tools/list` 跟随 `nextCursor` 累积注册，重复游标即停；随后把 `resources/list`、`resources/templates/list`、`prompts/list` 收敛到同一游标引擎，对外只暴露带类型的 walker。 |
| Raven [#822](https://github.com/EverMind-AI/Raven/pull/822) / [#891](https://github.com/EverMind-AI/Raven/pull/891) / [#1003](https://github.com/EverMind-AI/Raven/pull/1003) | 沙箱与升级：boxlite 安装提示指向实际运行的解释器而非全局 pip；`raven upgrade` 重建工具环境时保留已安装的 boxlite；源码 checkout 安装不再被提供页内升级，每条拒绝路径给出各自的恢复命令。 |
| Raven [#1058](https://github.com/EverMind-AI/Raven/pull/1058) | playbook 路由条件的参数与 prompt 在同一站点填充（密钥保留屏蔽），未声明的 `${params.*}` 引用改为校验失败，判定器不再收到带占位符的条件。 |
| [3x-ui #6830](https://github.com/MHSanaei/3x-ui/pull/6830) | `XUI_ENABLE_FAIL2BAN=false` 不再导致客户端 IP 停止记录：env 变量只门控封禁执行，扫描与在线统计照常入库，Windows 路径同样停用。 |
| [teamai-cli #996](https://github.com/Tencent/teamai-cli/pull/996) | 代码图谱补上 Scala：采集器白名单 `.scala` 并标记 `Main.scala`/`App.scala` 为关键文件，新增 Scala 抽取器，Java/Scala 混合项目不再产出只含 Java 的图。 |
| [AgentRecall #624](https://github.com/zszz3/AgentRecall/pull/624) | 会话趋势图日期可点击、新增自定义日期范围筛选（自然周期预设 + 精确区间，DST 安全），复用既有 `customDateRange` 通道。 |

全部已合并 PR：[is:pr author:yudongyouqing](https://github.com/pulls?q=is%3Apr+author%3Ayudongyouqing+is%3Amerged+-user%3Ayudongyouqing)


## 最近文章 ✍️

[博客](https://yudongyouqing.github.io/) · 以下列表由 GitHub Actions 自动更新

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->


## 活跃度 📈

![](./profile-3d-contrib/profile-season-animate.svg)


