<!--
  ali-novruz / ali-novruz  —  GitHub profile README
  ────────────────────────────────────────────────────────────
  DESIGN SYSTEM — keep these values everywhere, never introduce a new colour:
    bg / label   #0D1117
    accent       #1F6FEB   (filled = important)
    accent-light #58A6FF   (text + widget highlights)
    text         #C9D1D9
    muted        #8B949E
    success      #2EA043
  RULES
    - Colour = hierarchy. Filled accent badges are CTAs. Dark badges are supporting info.
    - Two badge styles only: for-the-badge (header + connect), flat-square (stack).
    - Every section: H2 with one emoji, then content, then `---`.
  TODO
    - Replace REPO_2 / REPO_3 with real repositories, or delete those cells.
    - Fill in the metric line under each project (stars, users, throughput, uptime…).
-->

<!-- ══════════════════════  HEADER  ══════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0D1117&text=Ali%20Novruz&fontSize=46&fontAlignY=38&fontColor=58A6FF&height=76&animation=fadeIn" alt="Ali Novruz" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=Backend+Engineer+%E2%80%94+Java+%2F+Kotlin+%2F+Spring;I+build+event-driven+systems+that+survive+failure;Kafka+%C2%B7+PostgreSQL+%C2%B7+Redis+%C2%B7+Kubernetes" alt="Backend Engineer — Java, Kotlin, Spring. I build event-driven systems that survive failure." />

<br/><br/>

<img src="https://img.shields.io/badge/Backend%20Engineer-1F6FEB?style=for-the-badge&labelColor=0D1117" alt="Backend Engineer" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Azerbaijan-1F6FEB?style=for-the-badge&labelColor=0D1117" alt="Based in Azerbaijan" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Open%20to%20work-2EA043?style=for-the-badge&labelColor=0D1117" alt="Open to work" />

<br/><br/>

<img src="https://img.shields.io/github/followers/ali-novruz?style=flat-square&logo=github&label=followers&labelColor=0D1117&color=1F6FEB" alt="Followers" />&nbsp;
<img src="https://img.shields.io/github/stars/ali-novruz?style=flat-square&logo=github&label=stars&labelColor=0D1117&color=1F6FEB" alt="Stars" />&nbsp;
<img src="https://komarev.com/ghpvc/?username=ali-novruz&style=flat-square&label=views&labelColor=0D1117&color=1F6FEB" alt="Profile views" />

</div>

---

<!-- ══════════════════════  ABOUT  ══════════════════════ -->

## 👋 &nbsp;About

I build **backend systems for healthcare**, mostly in Java and Kotlin on the Spring stack.
My work sits where distributed systems get uncomfortable: exactly-once delivery, recoverable
workflows, and databases that stay fast when the load doesn't cooperate.

- 🏥 &nbsp;Building a **Remote Patient Monitoring System** — continuous vitals ingestion at production scale
- 🧭 &nbsp;Working in: domain-driven design · event-driven microservices · observability · CI/CD
- 🌱 &nbsp;Going deeper on: JVM concurrency, Kotlin coroutines, Postgres query planning
- 💬 &nbsp;Ask me about: Kafka delivery semantics, the outbox pattern, Testcontainers-first CI

---

<!-- ══════════════════════  FEATURED WORK  ══════════════════════ -->

## 🚀 &nbsp;Featured work

<table border="0">
<tr>
<td width="50%" valign="top">

<a href="https://github.com/ali-novruz/RemotePatientMonitoringSystem">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ali-novruz&repo=RemotePatientMonitoringSystem&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&border_radius=8" alt="Remote Patient Monitoring System" />
</a>

Ingests continuous vitals from bedside devices and routes them to clinicians in real time.
Transactional outbox + Debezium for exactly-once delivery; sagas roll back cleanly when a
downstream service dies mid-workflow.

`Spring Boot` `Kafka` `PostgreSQL` `Redis` `K8s`

</td>
<td width="50%" valign="top">

<a href="https://github.com/ali-novruz/REPO_2">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ali-novruz&repo=REPO_2&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&border_radius=8" alt="Project two" />
</a>

Two or three lines: what it does, who it's for, and the one engineering decision you'd defend
in an interview. End with a number — stars, requests/sec, users, p99 latency.

`Kotlin` `Spring Cloud` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/ali-novruz/REPO_3">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ali-novruz&repo=REPO_3&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&border_radius=8" alt="Project three" />
</a>

Same shape. If you don't have a third project worth this space, delete this cell — an empty
slot reads better than a filler one.

`Java` `PostgreSQL`

</td>
<td width="50%" valign="top">

<br/>

**🔬 &nbsp;Currently working through**

| | |
| :--- | :--- |
| Messaging | Idempotent consumers, outbox + CDC |
| Workflows | Sagas with compensating actions |
| Testing | Testcontainers-first CI, contract tests |
| Data | BTREE/GiST/GIN strategy, Redis Streams |
| Ops | Prometheus metrics, SLO-driven alerting |

</td>
</tr>
</table>

---

<!-- ══════════════════════  STACK  ══════════════════════ -->

## 🧰 &nbsp;Stack

<sub>**LANGUAGES**</sub>

![Java](https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=ED8B00)
![Kotlin](https://img.shields.io/badge/Kotlin-0D1117?style=flat-square&logo=kotlin&logoColor=7F52FF)
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=3178C6)
![SQL](https://img.shields.io/badge/SQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)

<sub>**FRAMEWORKS & BUILD**</sub>

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-0D1117?style=flat-square&logo=springboot&logoColor=6DB33F)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-0D1117?style=flat-square&logo=spring&logoColor=6DB33F)
![Hibernate](https://img.shields.io/badge/Hibernate-0D1117?style=flat-square&logo=hibernate&logoColor=BCAE79)
![Gradle](https://img.shields.io/badge/Gradle-0D1117?style=flat-square&logo=gradle&logoColor=C9D1D9)
![Maven](https://img.shields.io/badge/Maven-0D1117?style=flat-square&logo=apachemaven&logoColor=C71A36)

<sub>**DATA & MESSAGING**</sub>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=FF4438)
![Kafka](https://img.shields.io/badge/Kafka-0D1117?style=flat-square&logo=apachekafka&logoColor=C9D1D9)
![Debezium](https://img.shields.io/badge/Debezium-0D1117?style=flat-square&logoColor=C9D1D9)

<sub>**INFRASTRUCTURE**</sub>

![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0D1117?style=flat-square&logo=kubernetes&logoColor=326CE5)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0D1117?style=flat-square&logo=githubactions&logoColor=2088FF)
![Nginx](https://img.shields.io/badge/Nginx-0D1117?style=flat-square&logo=nginx&logoColor=009639)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624)

<sub>**TESTING & OBSERVABILITY**</sub>

![JUnit5](https://img.shields.io/badge/JUnit5-0D1117?style=flat-square&logo=junit5&logoColor=25A162)
![Testcontainers](https://img.shields.io/badge/Testcontainers-0D1117?style=flat-square&logo=testcontainers&logoColor=C9D1D9)
![Prometheus](https://img.shields.io/badge/Prometheus-0D1117?style=flat-square&logo=prometheus&logoColor=E6522C)
![Grafana](https://img.shields.io/badge/Grafana-0D1117?style=flat-square&logo=grafana&logoColor=F46800)
![Swagger](https://img.shields.io/badge/Swagger-0D1117?style=flat-square&logo=swagger&logoColor=85EA2D)

---

<!-- ══════════════════════  ACTIVITY  ══════════════════════ -->

## 📊 &nbsp;Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ali-novruz&show_icons=true&include_all_commits=true&rank_icon=github&hide_border=true&border_radius=8&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&cache_seconds=21600" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=ali-novruz&show_icons=true&include_all_commits=true&rank_icon=github&hide_border=true&border_radius=8&theme=default&cache_seconds=21600" />
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ali-novruz&show_icons=true&include_all_commits=true&rank_icon=github&hide_border=true&border_radius=8&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E&cache_seconds=21600" alt="Ali Novruz's GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ali-novruz&layout=compact&langs_count=6&hide=html,css&hide_border=true&border_radius=8&bg_color=0D1117&title_color=58A6FF&text_color=8B949E&cache_seconds=21600" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ali-novruz&layout=compact&langs_count=6&hide=html,css&hide_border=true&border_radius=8&theme=default&cache_seconds=21600" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ali-novruz&layout=compact&langs_count=6&hide=html,css&hide_border=true&border_radius=8&bg_color=0D1117&title_color=58A6FF&text_color=8B949E&cache_seconds=21600" alt="Most used languages" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=C9D1D9&title_color=58A6FF&area=true&area_color=1F6FEB&hide_border=true&radius=8" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&theme=github-light&hide_border=true&radius=8" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=C9D1D9&area=true&area_color=1F6FEB&hide_border=true&radius=8" alt="Contribution activity over the last 31 days" />
</picture>

</div>

<!--
  OPTIONAL EXTRAS — uncomment only if you actually want them. Each one you add
  dilutes the ones above; the research is consistent that widget walls read as
  template-filling, not personality.

  Streak counter:
  <img src="https://streak-stats.demolab.com?user=ali-novruz&hide_border=true&border_radius=8&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9&sideNums=8B949E&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E" alt="Contribution streak" />

  Trophies:
  <img src="https://github-profile-trophy.vercel.app/?username=ali-novruz&theme=onedark&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="GitHub trophies" />
-->

---

<!-- ══════════════════════  CONNECT  ══════════════════════ -->

## 📬 &nbsp;Connect

<div align="center">

<a href="https://www.linkedin.com/in/ali-novruz-447115356/">
<img src="https://img.shields.io/badge/Let's%20talk%20on%20LinkedIn-1F6FEB?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" height="34" alt="LinkedIn — primary contact" />
</a>

<br/><br/>

<a href="mailto:alinovruz29@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" height="30" alt="Email" /></a>&nbsp;&nbsp;
<a href="https://github.com/ali-novruz/ali-novruz/releases/download/v1.0.0/ALINOVRUZ.pdf"><img src="https://img.shields.io/badge/Résumé-0D1117?style=for-the-badge&logo=adobeacrobatreader&logoColor=EC1C24" height="30" alt="Download résumé (PDF)" /></a>&nbsp;&nbsp;
<a href="https://gitlab.com/alinovruz29"><img src="https://img.shields.io/badge/GitLab-0D1117?style=for-the-badge&logo=gitlab&logoColor=FC6D26" height="30" alt="GitLab" /></a>&nbsp;&nbsp;
<a href="https://discordapp.com/users/1099172944711798824"><img src="https://img.shields.io/badge/Discord-0D1117?style=for-the-badge&logo=discord&logoColor=5865F2" height="30" alt="Discord" /></a>&nbsp;&nbsp;
<a href="https://www.instagram.com/ali__novruz"><img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=E4405F" height="30" alt="Instagram" /></a>&nbsp;&nbsp;
<a href="https://buymeacoffee.com/ali__novruz"><img src="https://img.shields.io/badge/Coffee-0D1117?style=for-the-badge&logo=buymeacoffee&logoColor=FFDD00" height="30" alt="Buy me a coffee" /></a>

</div>

---

<!-- ══════════════════════  FOOTER  ══════════════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake.svg" alt="Snake eating my contribution graph" />
</picture>

<br/>

<sub><i>Thanks for stopping by.</i></sub>

</div>
