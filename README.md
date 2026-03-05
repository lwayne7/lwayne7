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
    frontend: ["React 18/19", "TypeScript", "Taro 4", "Zustand", "TanStack Query"],
    backend:  ["NestJS 11", "Express", "TypeORM", "PostgreSQL", "JWT + Passport"],
    realtime: ["WebSocket (Socket.IO)", "SSE"],
    testing:  ["Vitest", "Playwright", "Lighthouse CI"],
    tools:    ["Vite 7", "GitHub Actions", "Vercel"]
  }
};
```

## Tech Stack

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React-18/19-61DAFB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Taro](https://img.shields.io/badge/Taro-4-0969da?style=flat-square)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-6-0170FE?style=flat-square&logo=antdesign&logoColor=white)
![NutUI](https://img.shields.io/badge/NutUI-React-FA2C19?style=flat-square)

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

Enterprise-grade visual form builder with **drag-and-drop**, **nested containers**, component linkage rules, **i18n** (zh/en), and React / JSON Schema code export. PWA offline support.

`React 19` `TypeScript 5.9` `Zustand` `Zod` `@dnd-kit` `Web Worker` `Vite 7`

**Highlights:**
- Custom multi-layer collision detection (success rate 78% → **98%+**, false positives **-80%**)
- Virtual scroll + memo for 1000+ components (FPS 35 → **55**, memory **-50%**)
- Immer-style patch undo/redo: history data **-95%** (373KB → 18KB), 50-step support
- AST expression engine (recursive descent parser) preventing XSS
- **131 unit + 22 E2E + 11 benchmark** tests, Lighthouse CI ≥ 80

</td>
<td width="50%">

### [EasyStay - Hotel Booking Platform](https://github.com/lwayne7/hotel-mobile-taro)

[![Admin Demo](https://img.shields.io/badge/Admin_Demo-Vercel-000?style=flat-square&logo=vercel)](https://hotel-management-eight-navy.vercel.app)
[![Mobile Demo](https://img.shields.io/badge/Mobile_Demo-Vercel-000?style=flat-square&logo=vercel)](https://hotel-mobile-taro.vercel.app)

Full-stack hotel booking system: **cross-platform mobile** (H5 / WeChat Mini Program / RN) + **admin dashboard** with real-time WebSocket notifications.

`Taro 4` `React 18/19` `NestJS 11` `TypeORM` `PostgreSQL` `WebSocket` `SSE`

**Highlights:**
- Taro 4 single codebase → H5 / WeChat Mini Program / React Native
- SSE + polling dual-channel real-time price updates with auto-reconnect
- WebSocket notifications: user-level targeting + role-based broadcast
- TanStack Query infinite scroll + Zustand cross-platform persistence
- JWT + Passport multi-role auth, virtual scroll for 10K+ hotel listings

> Repos: [hotel-mobile-taro](https://github.com/lwayne7/hotel-mobile-taro) (mobile) · [hotel-management](https://github.com/lwayne7/hotel-management) (backend + admin)

</td>
</tr>
</table>

<details>
<summary><b>Other Repositories</b></summary>
<br>

| Repository | Description | Tech |
|:--|:--|:--|
| [hotel-mobile](https://github.com/lwayne7/hotel-mobile) | Lightweight H5-only hotel booking app | React 19, Vite 7, Ant Design 6 |
| [Digital-watermarking](https://github.com/lwayne7/Digital-watermarking) | Digital watermarking algorithms | C++ |

</details>

## GitHub Stats

<div align="center">

<a href="https://github.com/lwayne7">
  <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=lwayne7&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub Streak"/>
</a>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lwayne7&theme=tokyonight" width="100%" alt="Contribution Graph"/>

</div>

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-lwayne7-181717?style=for-the-badge&logo=github)](https://github.com/lwayne7)
[![Email](https://img.shields.io/badge/Email-1584243719@qq.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:1584243719@qq.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
