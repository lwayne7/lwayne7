<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hi%2C%20I'm%20Wayne&fontSize=36&fontColor=fff&animation=fadeIn&fontAlignY=32&desc=Frontend%20Developer%20%7C%20Full-Stack%20Explorer&descSize=16&descAlignY=52" width="100%"/>

<p>
  <a href="https://github.com/lwayne7?tab=followers"><img src="https://img.shields.io/github/followers/lwayne7?label=Followers&style=social" alt="GitHub followers"></a>
  <img src="https://komarev.com/ghpvc/?username=lwayne7&color=blueviolet&style=flat-square" alt="Profile views">
</p>

**Master's Student @ Shanghai University | React & TypeScript | Full-Stack with NestJS**

</div>

## About Me

```javascript
const wayne = {
  education: "M.S. in Electronic Information @ Shanghai University (2024-2027)",
  focus: ["React Ecosystem", "Cross-Platform Dev", "Performance Optimization"],
  stack: {
    frontend:  ["React 18/19", "TypeScript", "Taro 4", "Zustand", "TanStack Query"],
    backend:   ["NestJS 11", "Express", "TypeORM", "PostgreSQL", "JWT + Passport"],
    realtime:  ["WebSocket (Socket.IO)", "SSE"],
    testing:   ["Vitest", "Playwright", "Lighthouse CI"],
    tools:     ["Vite 7", "GitHub Actions", "Vercel"],
  },
};
```

## Tech Stack

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React-18/19-61DAFB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Taro](https://img.shields.io/badge/Taro-4-0969da?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQyIDAtOC0zLjU4LTgtOHMzLjU4LTggOC04IDggMy41OCA4IDgtMy41OCA4LTggOHoiLz48L3N2Zz4=&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-6-0170FE?style=flat-square&logo=antdesign&logoColor=white)

**Backend & Infra**

![NestJS](https://img.shields.io/badge/NestJS-11-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white)

**Testing & DevOps**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

## Featured Projects

<table>
<tr>
<td width="50%">

### [FormCraft - Low-Code Form Builder](https://github.com/lwayne7/low-code-form)

[![Demo](https://img.shields.io/badge/Live_Demo-Vercel-000?style=flat-square&logo=vercel)](https://low-code-form.vercel.app)
[![CI](https://img.shields.io/github/actions/workflow/status/lwayne7/low-code-form/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/lwayne7/low-code-form/actions)

Enterprise-grade visual form builder with **drag-and-drop**, **nested containers**, component linkage rules, **i18n**, and React / JSON Schema code export.

`React 19` `TypeScript 5.9` `Zustand` `Zod` `@dnd-kit` `Web Worker` `Vite 7`

**Highlights:**
- Custom multi-layer collision detection algorithm (success rate 78% → **98%+**)
- Virtual scroll + memo optimization for 1000+ components (FPS 35 → **55**, mem -50%)
- Patch-based undo/redo: history data **-95%** (373KB → 18KB)
- AST-based expression engine (recursive descent parser) preventing XSS
- **131 unit + 22 E2E + 11 benchmark** tests, Lighthouse CI ≥ 80

</td>
<td width="50%">

### [EasyStay - Hotel Booking Platform](https://github.com/lwayne7/hotel-mobile-taro)

[![Management](https://img.shields.io/badge/Admin_Demo-Vercel-000?style=flat-square&logo=vercel)](https://hotel-management-eight-navy.vercel.app)
[![Mobile](https://img.shields.io/badge/Mobile_Demo-Vercel-000?style=flat-square&logo=vercel)](https://hotel-mobile-taro.vercel.app)

Full-stack hotel booking platform: **cross-platform mobile app** (H5 / WeChat Mini Program / RN) + **admin management dashboard** with real-time notifications.

`Taro 4` `React 18/19` `NestJS 11` `TypeORM` `PostgreSQL` `WebSocket` `SSE`

**Highlights:**
- Taro 4 single codebase → H5, WeChat Mini Program, React Native
- SSE + polling dual-channel real-time price updates
- WebSocket push notifications (user-level targeting + role broadcast)
- TanStack Query infinite scroll + Zustand persistent state
- JWT + Passport multi-role auth (merchant / admin), virtual scroll for 10K+ listings

</td>
</tr>
</table>

<details>
<summary><b>Other Repositories</b></summary>
<br>

| Repository | Description | Tech |
|:--|:--|:--|
| [hotel-management](https://github.com/lwayne7/hotel-management) | Hotel admin dashboard + NestJS backend API | React 19, NestJS, TypeORM, PostgreSQL |
| [hotel-mobile](https://github.com/lwayne7/hotel-mobile) | Lightweight H5-only hotel booking app | React 19, Vite 7, Ant Design 6 |
| [Digital-watermarking](https://github.com/lwayne7/Digital-watermarking) | Digital watermarking algorithms | C++ |

</details>

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=lwayne7&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&count_private=true" alt="GitHub Stats"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lwayne7&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&langs_count=6" alt="Top Languages"/>

</div>

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-lwayne7-181717?style=for-the-badge&logo=github)](https://github.com/lwayne7)
[![Email](https://img.shields.io/badge/Email-1584243719@qq.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:1584243719@qq.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
