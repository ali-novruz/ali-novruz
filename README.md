<!--
  ali-novruz / ali-novruz  —  GitHub profile README
  ══════════════════════════════════════════════════════════════
  REQUIRED FILES — commit these next to the README:
    assets/hero.svg      custom animated banner (yours alone, not a generator)
    assets/divider.svg   gradient section rule
  ══════════════════════════════════════════════════════════════
  PALETTE — never introduce a colour outside this list:
    #0D1117  base        #C9D1D9  text
    #39D0D8  cyan        #8B949E  muted
    #58A6FF  blue        #2EA043  success
    #A371F7  violet      #30363D  border
  The cyan→blue→violet gradient is the signature. It runs through the hero,
  every divider, and the header badges — that repetition is what makes the
  page read as one designed object instead of stacked widgets.
  ══════════════════════════════════════════════════════════════
  TODO — RemotePatientMonitoringSystem has no repo description or README on GitHub.
  It carries the whole backend-engineer claim on this page, so it is the single
  highest-value thing left to fix.
-->

<img src="./assets/hero.svg" width="100%" alt="Ali Novruz — Backend Engineer. Java, Kotlin, Spring, Kafka, PostgreSQL, Kubernetes." />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=640&lines=Exactly-once+delivery+over+unreliable+networks;Sagas+that+roll+back+when+services+die+mid-flight;Postgres+that+stays+fast+when+load+doesn't+cooperate" alt="Exactly-once delivery · Recoverable sagas · Fast Postgres under load" />

<br/><br/>

<img src="https://img.shields.io/badge/AZERBAIJAN-0D1117?style=for-the-badge&logo=googlemaps&logoColor=39D0D8" height="28" alt="Based in Azerbaijan" />&nbsp;
<img src="https://img.shields.io/badge/OPEN%20TO%20WORK-0D1117?style=for-the-badge&logo=briefcase&logoColor=2EA043" height="28" alt="Open to work" />&nbsp;
<img src="https://img.shields.io/github/followers/ali-novruz?style=for-the-badge&logo=github&label=FOLLOWERS&labelColor=0D1117&color=58A6FF" height="28" alt="Followers" />&nbsp;
<img src="https://komarev.com/ghpvc/?username=ali-novruz&style=for-the-badge&label=VIEWS&labelColor=0D1117&color=A371F7" height="28" alt="Profile views" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## <img src="https://img.shields.io/badge/01-39D0D8?style=flat-square&labelColor=0D1117" height="20" alt="" />&nbsp; About

I build **backend systems for healthcare**, mostly in Java and Kotlin on the Spring stack.
My work sits where distributed systems get uncomfortable: exactly-once delivery, recoverable
workflows, and databases that stay fast when the load doesn't cooperate.

<table border="0"><tr>
<td valign="top" width="50%">

**Right now**
- Remote Patient Monitoring — vitals ingestion at production scale
- DDD · event-driven microservices · observability · CI/CD
- Going deeper: JVM concurrency, coroutines, Postgres planning

</td>
<td valign="top" width="50%">

**Ask me about**
- Kafka delivery semantics and the outbox pattern
- Saga orchestration with compensating actions
- Testcontainers-first CI and contract testing

</td>
</tr></table>

<img src="./assets/divider.svg" width="100%" alt="" />

## <img src="https://img.shields.io/badge/02-58A6FF?style=flat-square&labelColor=0D1117" height="20" alt="" />&nbsp; Featured work

<!--
  Cards are hand-built rather than github-readme-stats pins on purpose: the public
  instance returns 503 under load, and a broken image is worse than no image.
  The star / language / last-commit badges are live shields.io data.
-->

<table border="0">
<tr>
<td width="50%" valign="top">

#### [Remote Patient Monitoring System](https://github.com/ali-novruz/RemotePatientMonitoringSystem)

<img src="https://img.shields.io/github/languages/top/ali-novruz/RemotePatientMonitoringSystem?style=flat-square&labelColor=0D1117&color=39D0D8" alt="" />
<img src="https://img.shields.io/github/last-commit/ali-novruz/RemotePatientMonitoringSystem?style=flat-square&labelColor=0D1117&color=8B949E" alt="" />

Ingests continuous vitals from bedside devices and routes them to clinicians in real
time. Transactional outbox for exactly-once delivery; sagas roll back cleanly when a
downstream service dies mid-workflow.

`Spring Boot` `Kafka` `PostgreSQL` `Redis` `K8s`

</td>
<td width="50%" valign="top">

#### [realtime-draft-messenger](https://github.com/ali-novruz/realtime-draft-messenger)

<img src="https://img.shields.io/github/stars/ali-novruz/realtime-draft-messenger?style=flat-square&labelColor=0D1117&color=58A6FF" alt="" />
<img src="https://img.shields.io/github/languages/top/ali-novruz/realtime-draft-messenger?style=flat-square&labelColor=0D1117&color=39D0D8" alt="" />

Chat that shows what the other person is typing *before* they hit send. Socket.IO
fan-out for the hot path, Redis for presence and ephemeral drafts, Postgres for
anything that has to survive a restart.

`Next.js` `Socket.IO` `Redis` `PostgreSQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [autodrive-recorder](https://github.com/ali-novruz/autodrive-recorder)

<img src="https://img.shields.io/github/stars/ali-novruz/autodrive-recorder?style=flat-square&labelColor=0D1117&color=58A6FF" alt="" />
<img src="https://img.shields.io/github/languages/top/ali-novruz/autodrive-recorder?style=flat-square&labelColor=0D1117&color=39D0D8" alt="" />

Background agent that ships OBS and ShadowPlay recordings to Google Drive. Resumable
uploads survive a dropped connection, and a stability check refuses to touch a file
the encoder is still writing to.

`Python` `Google Drive API` `Resumable uploads`

</td>
<td width="50%" valign="top">

#### [live-activity-tool](https://github.com/ali-novruz/live-activity-tool)

<img src="https://img.shields.io/github/stars/ali-novruz/live-activity-tool?style=flat-square&labelColor=0D1117&color=58A6FF" alt="" />
<img src="https://img.shields.io/github/languages/top/ali-novruz/live-activity-tool?style=flat-square&labelColor=0D1117&color=39D0D8" alt="" />

Privacy-first agent that streams Windows activity to a portfolio site in real time.
Filtering happens on the client, so the server never receives anything you didn't
explicitly agree to publish.

`Python` `React` `WebSockets`

</td>
</tr>
</table>

<div align="center"><sub><a href="https://github.com/ali-novruz?tab=repositories&sort=stargazers">→ &nbsp;all 10 repositories</a></sub></div>

<br/>

**Problems I'm working through right now**

| | | | | |
| :--- | :--- | :--- | :--- | :--- |
| **Messaging** | **Workflows** | **Testing** | **Data** | **Ops** |
| Idempotent consumers, outbox + CDC | Sagas with compensating actions | Testcontainers-first CI, contract tests | BTREE/GiST/GIN strategy, Redis Streams | Prometheus metrics, SLO-driven alerting |

<img src="./assets/divider.svg" width="100%" alt="" />

## <img src="https://img.shields.io/badge/03-A371F7?style=flat-square&labelColor=0D1117" height="20" alt="" />&nbsp; Stack

<table border="0">
<tr>
<td valign="top"><sub><b>LANGUAGES</b></sub></td>
<td>

![Java](https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=ED8B00)

</td>
</tr>
<tr>
<td valign="top"><sub><b>FRAMEWORKS</b></sub></td>
<td>

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-0D1117?style=flat-square&logo=springboot&logoColor=6DB33F)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-0D1117?style=flat-square&logo=spring&logoColor=6DB33F)
![Hibernate](https://img.shields.io/badge/Hibernate-0D1117?style=flat-square&logo=hibernate&logoColor=BCAE79)
![Gradle](https://img.shields.io/badge/Gradle-0D1117?style=flat-square&logo=gradle&logoColor=C9D1D9)
![Maven](https://img.shields.io/badge/Maven-0D1117?style=flat-square&logo=apachemaven&logoColor=C71A36)

</td>
</tr>
<tr>
<td valign="top"><sub><b>DATA</b></sub></td>
<td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=FF4438)
![Kafka](https://img.shields.io/badge/Kafka-0D1117?style=flat-square&logo=apachekafka&logoColor=C9D1D9)

</td>
</tr>
<tr>
<td valign="top"><sub><b>INFRA</b></sub></td>
<td>

![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0D1117?style=flat-square&logo=kubernetes&logoColor=326CE5)

</td>
</tr>
<tr>
<td valign="top"><sub><b>QUALITY</b></sub></td>
<td>

![JUnit5](https://img.shields.io/badge/JUnit5-0D1117?style=flat-square&logo=junit5&logoColor=25A162)
![Grafana](https://img.shields.io/badge/Grafana-0D1117?style=flat-square&logo=grafana&logoColor=F46800)
![Swagger](https://img.shields.io/badge/Swagger-0D1117?style=flat-square&logo=swagger&logoColor=85EA2D)

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="" />

## <img src="https://img.shields.io/badge/04-39D0D8?style=flat-square&labelColor=0D1117" height="20" alt="" />&nbsp; Activity

<div align="center">

<img src="https://img.shields.io/github/followers/ali-novruz?style=for-the-badge&logo=github&label=FOLLOWERS&labelColor=0D1117&color=39D0D8" height="26" alt="Followers" />&nbsp;
<img src="https://img.shields.io/github/stars/ali-novruz?style=for-the-badge&logo=github&label=STARS&labelColor=0D1117&color=58A6FF" height="26" alt="Total stars earned" />&nbsp;
<img src="https://img.shields.io/badge/PUBLIC%20REPOS-10-0D1117?style=for-the-badge&logo=github&logoColor=A371F7" height="26" alt="10 public repositories" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=ali-novruz&hide_border=true&border_radius=10&background=0D1117&ring=58A6FF&fire=A371F7&currStreakNum=C9D1D9&sideNums=8B949E&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=ali-novruz&hide_border=true&border_radius=10" />
  <img height="168" src="https://streak-stats.demolab.com?user=ali-novruz&hide_border=true&border_radius=10&background=0D1117&ring=58A6FF&fire=A371F7&currStreakNum=C9D1D9&sideNums=8B949E&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E" alt="Contribution streak" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&bg_color=0D1117&color=58A6FF&line=A371F7&point=39D0D8&title_color=58A6FF&area=true&area_color=1F6FEB&hide_border=true&radius=10" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&theme=github-light&hide_border=true&radius=10" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ali-novruz&bg_color=0D1117&color=58A6FF&line=A371F7&point=39D0D8&area=true&area_color=1F6FEB&hide_border=true&radius=10" alt="Contribution activity over the last 31 days" />
</picture>

</div>

<!--
  DELIBERATELY NOT HERE — both were verified broken on 2026-08-08:
    github-readme-stats.vercel.app   → 503 SERVICE_UNAVAILABLE (public instance is saturated)
    github-profile-trophy.vercel.app → failed to load
  If you want the stats card back, fork and deploy your own instance, then swap the host:
    gh repo fork anuraghazra/github-readme-stats --clone
  Self-hosted URLs are not rate-limited and will not 503 on your profile.
-->

<img src="./assets/divider.svg" width="100%" alt="" />

## <img src="https://img.shields.io/badge/05-58A6FF?style=flat-square&labelColor=0D1117" height="20" alt="" />&nbsp; Connect

<div align="center">

<br/>

<a href="https://www.linkedin.com/in/ali-novruz-447115356/">
<img src="https://img.shields.io/badge/LET'S%20TALK%20ON%20LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" height="38" alt="LinkedIn — primary contact" />
</a>

<br/><br/>

<a href="mailto:alinovruz29@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" height="30" alt="Email" /></a>&nbsp;
<a href="https://github.com/ali-novruz/ali-novruz/releases/download/v1.0.0/ALINOVRUZ.pdf"><img src="https://img.shields.io/badge/Résumé-0D1117?style=for-the-badge&logo=adobeacrobatreader&logoColor=EC1C24" height="30" alt="Download résumé (PDF)" /></a>&nbsp;
<a href="https://gitlab.com/alinovruz29"><img src="https://img.shields.io/badge/GitLab-0D1117?style=for-the-badge&logo=gitlab&logoColor=FC6D26" height="30" alt="GitLab" /></a>&nbsp;
<a href="https://discordapp.com/users/1099172944711798824"><img src="https://img.shields.io/badge/Discord-0D1117?style=for-the-badge&logo=discord&logoColor=5865F2" height="30" alt="Discord" /></a>&nbsp;
<a href="https://www.instagram.com/ali__novruz"><img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=E4405F" height="30" alt="Instagram" /></a>&nbsp;
<a href="https://buymeacoffee.com/ali__novruz"><img src="https://img.shields.io/badge/Coffee-0D1117?style=for-the-badge&logo=buymeacoffee&logoColor=FFDD00" height="30" alt="Buy me a coffee" /></a>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/ali-novruz/ali-novruz/output/github-contribution-grid-snake.svg" alt="Snake eating my contribution graph" />
</picture>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center"><sub><i>Thanks for stopping by.</i></sub></div>
