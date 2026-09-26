<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Hi%2C%20I'm%20Wang%20Lang%20(%E7%8E%8B%E7%90%85)&fontSize=38&fontColor=fff&animation=fadeIn&fontAlignY=32" width="100%"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&random=false&width=620&lines=Full-Stack+%26+AI+Application+Engineer+%F0%9F%9A%80;Building+High-Performance+Web+Systems+%E2%9A%A1;LLM+Agent+Workflows+%26+MCP+Tooling+%F0%9F%A4%96;Low-Code+Engine+Architecture+%F0%9F%9B%A0%EF%B8%8F;Resilient+Backend+with+NestJS+%26+Transactions+%F0%9F%9B%A1%EF%B8%8F" alt="Typing SVG" /></a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/lwayne7?label=Followers&style=social)](https://github.com/lwayne7?tab=followers)&nbsp;&nbsp;
<img src="https://komarev.com/ghpvc/?username=lwayne7&color=blueviolet&style=flat-square" alt="Profile views">&nbsp;&nbsp;
[![Master](https://img.shields.io/badge/Master-Shanghai%20University-blue?style=flat-square&logo=academia&logoColor=white)](https://www.shu.edu.cn)&nbsp;&nbsp;
[![GPA](https://img.shields.io/badge/GPA-3.7%20%2F%204.0-success?style=flat-square)](https://github.com/lwayne7)&nbsp;&nbsp;
[![Target](https://img.shields.io/badge/Seeking-2027%20Campus%20Recruitment-orange?style=flat-square)](https://github.com/lwayne7)

<br/>

> 专注 **前端性能极致优化**、**复杂低代码架构** 与 **大模型工程化 (Agent / MCP / RAG / 工作流编排)**。<br/>
> 坚持「代码存在 ≠ 真实收益」，推崇**以事实说话、以可核验基准度量系统**的工程哲学。

</div>

<br/>

## 💡 About Me

```typescript
const engineer = {
  name: "Wang Lang (王琅)",
  role: "Full-Stack & AI Application Engineer",
  education: {
    school: "Shanghai University (上海大学)",
    degree: "M.S. in Electronic Information (2024.09 - 2027.06 预计)",
    metrics: "GPA 3.7/4.0 · CET-6 · 2x University Second-Class Scholarship"
  },
  internships: [
    { company: "China Literature / Tencent PCG (阅文集团)", role: "Frontend Developer Intern", period: "2026.07 - 2026.09" },
    { company: "Shanghai Linghui Tech (上海灵绘动影)", role: "Full-Stack & AI Application Engineer", period: "2026.04 - 2026.06" }
  ],
  bootcamps: [
    "ByteDance Engineering Bootcamp (字节跳动工程训练营)",
    "Ctrip Frontend Bootcamp (携程前端训练营)"
  ],
  engineeringPrinciples: [
    "Verify before commit: 代码存在 ≠ 真实收益，数据必须前后同源可复现",
    "Performance first: 细粒度订阅收敛无用重渲染，虚拟化应对海量 DOM 节点",
    "Defensive architecture: 条件更新防并发竞态，AST 求值替代 eval/new Function"
  ]
};
```

<br/>

## 🚀 Featured Open Source Projects

<table>
  <!-- Row 1: FormCraft & EasyStay -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/lwayne7/low-code-form">🛠️ FormCraft · 低代码表单引擎</a></h3>
      <p align="center"><strong>Enterprise Low-Code Form Builder & Runtime Engine</strong></p>
      <div align="center">
        <a href="https://low-code-form.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
        <a href="https://github.com/lwayne7/low-code-form/actions"><img src="https://img.shields.io/github/actions/workflow/status/lwayne7/low-code-form/ci.yml?branch=main&style=for-the-badge&label=CI" alt="CI Status"/></a>
      </div>
      <br/>
      面向复杂交互与嵌套场景的组件树低代码表单构建器，提供 11 种组件统一注册表、嵌套画布与 Schema 驱动递归渲染运行时。
      <br/><br/>
      <p align="center">
        <code>React 18/19</code> <code>TypeScript</code> <code>Ant Design</code> <code>Zustand</code> <code>Zod</code> <code>Vitest</code>
      </p>
      <table>
        <tr><th>核心机制</th><th>实测核验基准</th></tr>
        <tr><td>千级组件虚拟化</td><td>挂载行数 <b>1000 → 14</b>（降载 98.6%）</td></tr>
        <tr><td>画布就绪耗时</td><td>就绪延迟 <b>557ms → 185ms</b>（提速 66.8%）</td></tr>
        <tr><td>JS 堆内存优化</td><td>强制 GC 后堆内存 <b>164MB → 31MB</b></td></tr>
        <tr><td>Typed Patch 撤销</td><td>100 次基准历史 JSON 体积<b>减少 95.1%</b></td></tr>
        <tr><td>安全表达式求值</td><td><b>受限 AST 求值</b> + 解析缓存替代 <code>new Function</code></td></tr>
        <tr><td>工程质量跑分</td><td>Lighthouse CI <b>性能 0.99 / 无障碍 0.96</b></td></tr>
      </table>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/lwayne7/hotel-mobile-taro">🏨 易宿酒店预订平台 · 多端协同</a></h3>
      <p align="center"><strong>Full-Stack Hotel Booking & Management (Ctrip Bootcamp)</strong></p>
      <div align="center">
        <a href="https://hotel-mobile-taro.vercel.app"><img src="https://img.shields.io/badge/Mobile_Demo-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Mobile Demo"/></a>
        <a href="https://hotel-management-eight-navy.vercel.app"><img src="https://img.shields.io/badge/Admin_Demo-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Admin Demo"/></a>
      </div>
      <br/>
      携程前端训练营精选项目：覆盖 PC 管理后台全栈及 Taro 跨端移动应用（H5 / 微信小程序 / React Native）。
      <br/><br/>
      <p align="center">
        <code>Taro 4</code> <code>React</code> <code>NestJS</code> <code>TypeORM</code> <code>PostgreSQL</code> <code>Socket.IO / SSE</code>
      </p>
      <table>
        <tr><th>核心机制</th><th>实现细节与保障</th></tr>
        <tr><td>并发 401 静默刷新</td><td>双 Token + 队列，<b>本地 100 并发 401 仅刷新 1 次</b>并全重放</td></tr>
        <tr><td>防跨日超卖事务</td><td>入住日期集合在<b>单事务内条件更新</b>并校验影响行数，超卖整单回滚</td></tr>
        <tr><td>支付回调防重放</td><td><b>HMAC + 时间窗校验</b>模拟支付回调，事件唯一键防重复入库</td></tr>
        <tr><td>三层权限防护</td><td>服务端实施 <b>RBAC + 资源所有权 + 审核五态</b>三层强校验</td></tr>
        <tr><td>全链路可观测</td><td><code>prom-client</code> 自定义请求计数/耗时直方图 + Web Vitals 端点</td></tr>
        <tr><td>生产级容器交付</td><td>配置多环境 CI 流水线与 <b>Docker 多阶段构建</b>交付</td></tr>
      </table>
    </td>
  </tr>
  <!-- Row 2: code-tape & AI Engineering -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/lwayne7/code-tape">📼 code-tape · 代码录码带回放引擎</a></h3>
      <p align="center"><strong>Interactive Code Recording & Playback (ByteDance Bootcamp)</strong></p>
      <div align="center">
        <img src="https://img.shields.io/badge/ByteDance-Camp%20Project-000000?style=for-the-badge&logo=bytedance" alt="ByteDance Camp"/>
        <img src="https://img.shields.io/badge/TypeScript-Core-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
      </div>
      <br/>
      字节跳动工程训练营精选项目：面向开发者场景的高保真代码录制与交互式步骤回放引擎。
      <br/><br/>
      <p align="center">
        <code>TypeScript</code> <code>Vitest</code> <code>Node.js</code> <code>Web Audio</code>
      </p>
      <ul>
        <li><b>分级资源校验与对象复用</b>：校验录制包时长、事件数与资源体积，必需资产与可选媒体分级处理；复用已读取对象避免重复解析，本地媒体包<b>对象读取从 10 降至 5 次</b>。</li>
        <li><b>媒体缺失平滑降级</b>：当可选音视频媒体损坏或丢失时，系统自动优雅降级为纯代码高亮步骤回放，杜绝回放崩溃。</li>
        <li><b>并发状态防护</b>：构建重命名与软删除幂等 API，通过<b>条件更新与字段级回写</b>杜绝后台校验覆盖新标题与并发竞态。</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🤖 AI 工程化与 Agent 工作流落地</h3>
      <p align="center"><strong>LLM Agents, MCP Protocols & ComfyUI Workflows</strong></p>
      <div align="center">
        <img src="https://img.shields.io/badge/MCP-Protocol-4B32C3?style=for-the-badge" alt="MCP"/>
        <img src="https://img.shields.io/badge/RAG-Vector%20Sync-2496ED?style=for-the-badge" alt="RAG"/>
        <img src="https://img.shields.io/badge/ComfyUI-Workflows-FF6F00?style=for-the-badge" alt="ComfyUI"/>
      </div>
      <br/>
      深度实践大厂业务及创业团队实际落地场景的工业级 AI 应用开发体系。
      <br/><br/>
      <p align="center">
        <code>Model Context Protocol (MCP)</code> <code>RAG</code> <code>ComfyUI</code> <code>Prompt Engineering</code>
      </p>
      <ul>
        <li><b>源码知识库与 Agent</b>：跨 3 仓建设 <b>500+ 条页面索引知识库</b>，随提交钩子增量更新；封装 <b>6 类只读 MCP 工具</b>支撑架构查询 Agent；<code>yknow-kb-sync</code> 同步条目并触发向量化。</li>
        <li><b>Agent 代码审查流</b>：把人工 CR 升级为 <b>43 条规则扫描 + Agent 复核</b>分层审查，diff 行定位结合页面规则出具审查报告。</li>
        <li><b>模型调度与子图裁剪</b>：8 个文生图/视频模型自调度轮询（1.5–4s），远端任务 ID 持久化；ComfyUI 4 工作流接入并实现<b>子图展开与依赖裁剪（122 展平裁剪至 112 节点）</b>，密钥服务端保管不泄露。</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

## 🛠️ Tech Stack & Tooling

<div align="center">

| 领域分类 | 核心技能体系与技术栈 |
| :--- | :--- |
| **AI 应用与 Agent 工具链** | `MCP Tools 封装` · `Agent Workflow 编排` · `Context & Prompt Engineering` · `RAG 知识库与向量化` · `ComfyUI 私有工作流集成` |
| **前端开发与跨端框架** | `TypeScript` · `React 18/19` · `Next.js` · `Ant Design` · `Vue 3` · `Taro (小程序/H5/RN)` · `Zustand` · `TanStack Query` |
| **服务端架构与实时系统** | `Node.js` · `NestJS` · `PostgreSQL` · `TypeORM` · `Redis` · `SSE / WebSocket (Socket.IO)` · `RBAC 鉴权` · `并发事务与条件更新` |
| **工程质量、测试与运维** | `Vitest / Jest` · `Playwright (E2E)` · `Docker 多阶段构建` · `GitHub Actions CI/CD` · `Lighthouse CI` · `prom-client / Web Vitals` |

<br/>

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,vue,nodejs,nestjs,postgres,redis,docker,githubactions,git,tailwind&theme=dark" alt="Tech Stack Icons" />

<br/><br/>

<img src="https://img.shields.io/badge/React-18%2F19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
<img src="https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/NestJS-11-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/>
<img src="https://img.shields.io/badge/PostgreSQL-TypeORM-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Taro-Cross--Platform-0969DA?style=for-the-badge" alt="Taro"/>
<img src="https://img.shields.io/badge/Ant_Design-5.0-0170FE?style=for-the-badge&logo=antdesign&logoColor=white" alt="Ant Design"/>
<img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>

</div>

<br/>

## 📊 GitHub Stats & Dynamic Activity

<div align="center">

<a href="https://github.com/lwayne7">
  <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=lwayne7&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub Streak"/>
</a>

<br/><br/>

<a href="https://github.com/lwayne7">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=lwayne7&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000" alt="Wang Lang's GitHub Stats" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lwayne7&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000" alt="Top Languages" />
</a>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lwayne7&theme=tokyo-night&hide_border=true&bg_color=00000000" width="100%" alt="Contribution Graph"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lwayne7/lwayne7/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lwayne7/lwayne7/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/lwayne7/lwayne7/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

<br/>

## 📬 Connect With Me

<div align="center">

<p>如果你正在寻找兼具<b>扎实全栈工程基本功</b>与<b>前沿大模型 / Agent 工程落地能力</b>的年轻开发者，欢迎随时联系我：</p>

[![Email](https://img.shields.io/badge/Email-1584243719@qq.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:1584243719@qq.com)&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-lwayne7-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lwayne7)&nbsp;&nbsp;
[![Phone](https://img.shields.io/badge/Phone-137--3219--1244-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:13732191244)

<br/><br/>

<sub><i>"Engineering excellence comes from verification, not assumption." · 感谢您的访问与关注！</i></sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
