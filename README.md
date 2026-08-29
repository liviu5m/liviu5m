<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16161e,100:1a1b26&height=120&section=header&text=liviu5m&fontSize=46&fontColor=9ece6a&fontAlignY=55&desc=full-stack%20developer%20%C2%B7%20competitive%20programmer&descAlignY=80&descColor=7dcfff&fontFamily=JetBrains%20Mono" width="100%"/>

<a href="https://github.com/liviu5m">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2800&pause=900&color=9ECE6A&center=true&vCenter=true&width=650&lines=fast-learner;fully+complex+projects+by+10;structured+self-study+of+languages+%26+paradigms+since+14;650%2B+DSA+problems+solved;top+10+nationally+in+math+%C2%B7+top+6+in+informatics" alt="Typing SVG" />
</a>

</div>

<br/>

```
██╗     ██╗██╗   ██╗██╗██╗   ██╗██████╗ ███╗   ███╗
██║     ██║██║   ██║██║██║   ██║██╔══██╗████╗ ████║
██║     ██║██║   ██║██║██║   ██║██████╔╝██╔████╔██║
██║     ██║╚██╗ ██╔╝██║██║   ██║██╔══██╗██║╚██╔╝██║
███████╗██║ ╚████╔╝ ██║╚██████╔╝██║  ██║██║ ╚═╝ ██║
╚══════╝╚═╝  ╚═══╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝
```

<div align="center">

`[1] home.md`&nbsp;&nbsp;`[2] projects/`&nbsp;&nbsp;`[3] experience.log`&nbsp;&nbsp;`[4] config.lua`
<sub>press <code>j</code>/<code>k</code> to scroll this file, or just... scroll</sub>

</div>

---

### `[1] home.md`

```lua
-- ~/.config/nvim/whoami.lua
local dev = {
  name        = "Moțpan Liviu",
  role        = "high school student · full-stack developer",
  location    = "Nisporeni, Republic of Moldova",
  self_study  = 14,   -- age, structured study of languages & paradigms begins
  fast_learner= true, -- school is effortless, time reinvested into deep study
  focus       = { "microservices", "systems programming", "competitive programming" },
}

return dev
```

I build production-style, microservice-based full-stack systems (Spring Boot, React/Next.js)
and low-level systems software in C — with a competitive-programming background from national
Mathematics & Informatics Olympiads underneath all of it.

<table>
<tr><td>🏆</td><td><b>3× Honorable Mention</b> (4th place) &amp; <b>3× 3rd place</b> — National Olympiad of Moldova, Math &amp; Informatics</td></tr>
<tr><td>📈</td><td>Consistent national ranking: <b>Top 10</b> in Mathematics, <b>Top 6</b> in Informatics</td></tr>
<tr><td>🧩</td><td><b>650+</b> DSA problems solved on LeetCode</td></tr>
<tr><td>🎓</td><td>Liceul Teoretic "Boris Cazacu" — 9.87/10 (10th) · 9.95/10 (11th) — graduating 2027</td></tr>
<tr><td>🗣️</td><td>Romanian (native) · English (B2, Cambridge) · French (conversational)</td></tr>
</table>

---

### `[2] projects/`

<details open>
<summary><b>FoodRoute</b> — full-stack food ordering platform (microservices)</summary>
<br/>

```diff
+ React 19 · TypeScript · Tailwind · Spring Boot · MongoDB · Stripe · Cloudinary
+ microservices backend: auth, product, order, cart, review, user — Spring Boot + MongoDB
+ Clerk + Google OAuth auth, role-based access separating customer / admin flows
+ Stripe checkout, Cloudinary image pipelines, admin dashboard w/ sales analytics
+ React 19 frontend, TanStack Query + Zustand for real-time cart & inventory
```
🔗 [food-route.vercel.app](https://food-route.vercel.app/)
</details>

<details>
<summary><b>Apointy</b> — microservice appointment scheduling platform</summary>
<br/>

```diff
+ Spring Boot · React · TypeScript · Eureka · RabbitMQ · PostgreSQL · Docker Compose
+ Eureka service registry + API Gateway (JWT verification, Google OAuth2 login)
+ user-service: registration, account sync, email verification, password reset via RabbitMQ
+ booking-service + notification-service: scheduling, availability queues, reminders
```
🔗 [apointy.vercel.app](https://apointy.vercel.app/)
</details>

<details>
<summary><b>Evolve</b> — fitness & wellness tracking platform</summary>
<br/>

```diff
+ TypeScript · React · Java · Spring Boot
+ workout planning, meal tracking, progress monitoring, grocery management
+ decoupled TS frontend + Java/Spring Boot backend, same patterns as FoodRoute/Apointy
+ data model built around recurring domains for trend & history views
```
🔗 [evolveapp.vercel.app](https://evolveapp.vercel.app/)
</details>

<details>
<summary><b>Hive</b> — full-stack social platform</summary>
<br/>

```diff
+ TypeScript · Java · Spring Boot · JWT · Google OAuth2
+ posts, real-time chat, social graph, customizable profile pages
+ JWT sessions, OTP email verification with resend/expiry logic
+ auth-guarded routing separating onboarding from protected routes
```
🔗 [gethive.vercel.app](https://gethive.vercel.app/)
</details>

<details>
<summary><b>kern</b> — custom Unix-like shell</summary>
<br/>

```diff
+ C · POSIX · GNU Readline
+ POSIX-style interactive shell from scratch: prompt, built-ins, PATH-based execution
+ process management: pipelines, command chaining (&&), I/O redirection, background jobs
+ GNU Readline integration: persistent history, TAB completion
```
🔗 [github.com/liviu5m/kern](https://github.com/liviu5m/kern)
</details>

---

### `[3] experience.log`

```
Age 14    * growth      structured self-study: languages, paradigms, mental models
Ongoing   * competition National Olympiad — top 10 math / top 6 informatics nationally
650+      * practice    DSA problems solved, LeetCode
10th grd  * education   Liceul Teoretic "Boris Cazacu" — 9.87/10
11th grd  * education   Liceul Teoretic "Boris Cazacu" — 9.95/10 · grad. 2027
```

**certifications** — Cambridge English (B2 First) · Certiport: JavaScript, Databases, Network Security

---

### `[4] config.lua` — stack

<div align="center">

![JavaScript](https://img.shields.io/badge/-JavaScript-1a1b26?style=for-the-badge&logo=javascript&logoColor=f7768e)
![TypeScript](https://img.shields.io/badge/-TypeScript-1a1b26?style=for-the-badge&logo=typescript&logoColor=7dcfff)
![Python](https://img.shields.io/badge/-Python-1a1b26?style=for-the-badge&logo=python&logoColor=9ece6a)
![Java](https://img.shields.io/badge/-Java-1a1b26?style=for-the-badge&logo=openjdk&logoColor=ff9e64)
![C](https://img.shields.io/badge/-C-1a1b26?style=for-the-badge&logo=c&logoColor=bb9af7)
![C++](https://img.shields.io/badge/-C%2B%2B-1a1b26?style=for-the-badge&logo=cplusplus&logoColor=7dcfff)
![PHP](https://img.shields.io/badge/-PHP-1a1b26?style=for-the-badge&logo=php&logoColor=9ece6a)
![SQL](https://img.shields.io/badge/-SQL-1a1b26?style=for-the-badge&logo=postgresql&logoColor=ff9e64)

![React](https://img.shields.io/badge/-React-1a1b26?style=for-the-badge&logo=react&logoColor=7dcfff)
![Next.js](https://img.shields.io/badge/-Next.js-1a1b26?style=for-the-badge&logo=nextdotjs&logoColor=f7f7f7)
![Tailwind](https://img.shields.io/badge/-Tailwind-1a1b26?style=for-the-badge&logo=tailwindcss&logoColor=7dcfff)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-1a1b26?style=for-the-badge&logo=springboot&logoColor=9ece6a)
![FastAPI](https://img.shields.io/badge/-FastAPI-1a1b26?style=for-the-badge&logo=fastapi&logoColor=9ece6a)
![Laravel](https://img.shields.io/badge/-Laravel-1a1b26?style=for-the-badge&logo=laravel&logoColor=f7768e)

![Docker](https://img.shields.io/badge/-Docker-1a1b26?style=for-the-badge&logo=docker&logoColor=7dcfff)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-1a1b26?style=for-the-badge&logo=postgresql&logoColor=7dcfff)
![MongoDB](https://img.shields.io/badge/-MongoDB-1a1b26?style=for-the-badge&logo=mongodb&logoColor=9ece6a)
![MySQL](https://img.shields.io/badge/-MySQL-1a1b26?style=for-the-badge&logo=mysql&logoColor=ff9e64)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-1a1b26?style=for-the-badge&logo=rabbitmq&logoColor=ff9e64)

![Git](https://img.shields.io/badge/-Git-1a1b26?style=for-the-badge&logo=git&logoColor=f7768e)
![Linux](https://img.shields.io/badge/-Linux-1a1b26?style=for-the-badge&logo=linux&logoColor=f7f7f7)
![Neovim](https://img.shields.io/badge/-Neovim-1a1b26?style=for-the-badge&logo=neovim&logoColor=9ece6a)
![Figma](https://img.shields.io/badge/-Figma-1a1b26?style=for-the-badge&logo=figma&logoColor=bb9af7)

</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=liviu5m&show_icons=true&theme=tokyonight&hide_border=true&bg_color=16161e&title_color=9ece6a&icon_color=7dcfff&text_color=c0caf5" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=liviu5m&theme=tokyonight&hide_border=true&background=16161e&ring=9ece6a&fire=ff9e64&currStreakLabel=c0caf5" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=liviu5m&layout=compact&theme=tokyonight&hide_border=true&bg_color=16161e&title_color=9ece6a&text_color=c0caf5" width="49%"/>

</div>

---

<div align="center">

```
-- STATUS LINE --------------------------------------------------------
 NORMAL │ liviu5m │  main │ UTF-8 │ 100%
------------------------------------------------------------------------
```

📫 **[motpanliviuwork@gmail.com](mailto:motpanliviuwork@gmail.com)** · 🧠 **[LeetCode](https://leetcode.com/u/motpanliviu)** · 🌐 **[Portfolio](https://liviu5m.vercel.app/)**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,100:16161e&height=3&section=footer" width="100%"/>

</div>
