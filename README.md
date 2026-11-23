<div align="center">

<h1>陈明欢 · chenminghuan-cn</h1>

<p><b>AI 应用工程师 · Agent 平台 / Product Engineer</b><br>
产品出身，现在自己写系统 —— 从架构、前后端到 K8s 运维一个人走完。</p>

<p>
  <a href="mailto:chenminghuan.cn@gmail.com"><img src="https://img.shields.io/badge/chenminghuan.cn@gmail.com-EA4335?logo=gmail&logoColor=white" alt="email"></a>
  <a href="https://chenminghuan.com"><img src="https://img.shields.io/badge/blog-chenminghuan.com-4f46e5" alt="blog"></a>
  <img src="https://img.shields.io/badge/武汉-555" alt="location">
</p>

</div>

## 在做什么

**企业级 Agent 中台**——让 Agent 能被企业内网接受的三件事：

- **凭据不出平台**：模型 key、内部系统签名、媒体账户密钥不进沙箱，由平台反代按应用/技能维度鉴权转发
- **权限可收敛**：应用与代码权限隔离，技能网关对每个内部系统单独鉴权，不给 Agent 一把万能钥匙
- **成本可归集**：对外只开 OpenAPI，个人密钥 + 白名单准入，调用与花费全链路可追溯

单人 0→1：98 个接口 / 77 张表 / 60 个测试文件；沙箱唤醒 30-40s→11s，镜像包 75MB→2.9MB。

## 开源项目

### [job-hunter-hub](https://github.com/chenminghuan-cn/job-hunter-hub)
`Python` `FastAPI` `React` `SQLite` · 个人**应聘中台**

8 个招聘渠道（猎聘 / BOSS / 领英 / 小红书 / X / 脉脉 / 即刻 / 公众号）的岗位由自己的 Agent 采集进来，
中台负责幂等入库、四套状态机（岗位 / 公司 / 联系人 / 渠道）、JD 匹配预审、按岗位定制简历。
外放接口用 A2A JSON-RPC + 每 Agent 独立 HMAC 签名 + 按权限分发工具——采集 Agent 碰不到联系人，
舆情/预审 Agent 改不了采集侧的原始事实。

<img src="https://raw.githubusercontent.com/chenminghuan-cn/job-hunter-hub/main/docs/screenshots/dashboard.png" width="800">

---

### [pi-web](https://github.com/chenminghuan-cn/pi-web)
`JavaScript` `Node` · Codex 风格的 Web UI for π

在浏览器里浏览、fork、驱动你的 agent 会话，不用守终端。

### [pi-session-index](https://github.com/chenminghuan-cn/pi-session-index)
`JavaScript` `SQLite` · 给 π 的 JSONL 会话建索引

406 个会话从 **5.9s 降到 8ms**，且完全不改动 π 本身。

## 技术栈

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
</p>

## 一点背景

- **2021 - 至今**：投放 / 归因 / BI / 直播四套内部系统从 0-1，成为公司投放与经营数据的事实标准，支撑年消耗 10 亿+
- **2026**：AI 产品交付 → Agent 中台独立开发；期间做过 AI 出海产品（日语 / 繁中）的立项到投放验证
- 擅长把模糊业务诉求收敛成可验收指标；习惯先验证最小闭环，再把 AI 能力翻译成企业能接受的安全边界
- 自己喜欢的活：让 Agent 自己长出可部署应用（生成 → 预览 → 版本化 → 回滚 → 自检）

<div align="center">
<sub>用 <a href="https://github.com/chenminghuan-cn/job-hunter-hub">job-hunter-hub</a> 管着自己的求职流程 · 想聊 Agent 平台 / AI 应用落地，邮件最快</sub>
</div>
