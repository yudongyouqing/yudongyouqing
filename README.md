# 关于我 👋

> 充满鲜花的世界到底在哪里，如果它真的存在那么我一定会去。

[![Blog](https://img.shields.io/badge/Blog-Can%20you%20feel%20my%20world-0f766e?style=flat-square)](https://yudongyouqing.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-yudongyouqing-24292f?style=flat-square&logo=github)](https://github.com/yudongyouqing)
[![Go](https://img.shields.io/badge/Golang-Backend-00ADD8?style=flat-square&logo=go&logoColor=white)](https://go.dev/)

你好，我是 **clearlove13**。

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=0F766E&vCenter=true&width=420&lines=Go+%E5%90%8E%E7%AB%AF%E5%BC%80%E5%8F%91%3B%E5%BA%95%E5%B1%82%E5%8E%9F%E7%90%86%E7%88%B1%E5%A5%BD%E8%80%85%3BACMer%3Blol%E6%B5%B7%E6%96%97%E5%A4%A7%E7%8E%8B)](https://git.io/typing-svg)


## 开源贡献 🧩

### 已合并

| 项目 | 工作 |
| --- | --- |
| MyGo [#1910](https://github.com/egoist/mygo/pull/1910) | 修复单实例锁的生命周期与并发启动问题；持续等待锁释放、兼容旧版实例的改进由上游整合至 #1909，以 Co-author 身份合入 main（#1910 因方案重叠关闭）。 |
| Raven [#1264](https://github.com/EverMind-AI/Raven/pull/1264) | Agent Plugin 账本从按包名登记改为按 workspace 隔离（v2 记录），覆盖或删除前校验宿主创建的标记；v1 记录保留为未验证来源，损坏账本拒载，失败的删除可重试。 |
| Raven [#955](https://github.com/EverMind-AI/Raven/pull/955) / [#1002](https://github.com/EverMind-AI/Raven/pull/1002) / [#1056](https://github.com/EverMind-AI/Raven/pull/1056) | 子代理 DAG：DAG 节点改经 `sandbox_factory` 逐节点构建执行器，`tools.sandbox` 配置不再被静默绕过；replan 命中的那一轮为 skipped/cancelled 节点补发终态帧；TUI 对从未运行的节点不再显示 0s 时长。 |
| Raven [#825](https://github.com/EverMind-AI/Raven/pull/825) / [#859](https://github.com/EverMind-AI/Raven/pull/859) | MCP 客户端分页：`tools/list` 跟随 `nextCursor` 累积注册，重复游标即停；随后把 `resources/list`、`resources/templates/list`、`prompts/list` 收敛到同一游标引擎，对外只暴露带类型的 walker。 |
| [teamai-cli #996](https://github.com/Tencent/teamai-cli/pull/996) | 代码图谱补上 Scala：采集器白名单 `.scala` 并标记 `Main.scala`/`App.scala` 为关键文件，新增 Scala 抽取器，Java/Scala 混合项目不再产出只含 Java 的图。 |
| [3x-ui #6830](https://github.com/MHSanaei/3x-ui/pull/6830) | `XUI_ENABLE_FAIL2BAN=false` 不再导致客户端 IP 停止记录：env 变量只门控封禁执行，扫描与在线统计照常入库，Windows 路径同样停用。 |

### 待合并

| 项目 | 工作 |
| --- | --- |
| Raven [#1321](https://github.com/EverMind-AI/Raven/pull/1321) | 生成的参与者收到的 tool call 被序列化成 dataclass 字符串，读不到调用名与嵌套参数；改为投影成纯 `id`/`name`/`arguments` 映射，与宿主响应递归解耦，保留原回退行为。 |
| [FreeSWITCH #3203](https://github.com/signalwire/freeswitch/pull/3203) | v1.11.2 引入的 inject-DoS 防护误吞了 `switch_rtp_break()` 唤醒读线程的 break ping，无 timer 的 RTP 会话挂断延迟从 ~20ms 涨到 ~5s；修正判据让该 ping 直通。 |


## 最近文章 ✍️

<!-- BLOG-POST-LIST:START -->
- [Claude 的记忆系统：显著性、做梦，和 MEMORY.md 的前 200 行](https://yudongyouqing.github.io/2026/11/16/claude-memory-takeaways/)
- [GoFrame 数组参数静默绑定失败：比不支持更坑的半吊子支持](https://yudongyouqing.github.io/2026/10/20/goframe-indexed-array-binding/)
- [Go 语言中的 defer：常见用法与避坑指南](https://yudongyouqing.github.io/2026/10/20/go-defer/)
- [一个流水水水水账](https://yudongyouqing.github.io/2026/06/16/yi-ge-liu-shui-shui-shui-zhang/)
- [中文分词-最大匹配算法](https://yudongyouqing.github.io/2026/06/04/%E4%B8%AD%E6%96%87%E5%88%86%E8%AF%8D-%E6%9C%80%E5%A4%A7%E5%8C%B9%E9%85%8D%E7%AE%97%E6%B3%95/)
<!-- BLOG-POST-LIST:END -->


## 活跃度 📈

![](./profile-3d-contrib/profile-season-animate.svg)


