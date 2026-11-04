<!--
  Paleta herdada do portfólio (felipegco.github.io → src/app/globals.css):
    ground  #0a0a0a   paper #141416   ink #ededed   muted #a1a1aa
    accent  #3b82f6   neon  #60a5fa   light #93c5fd
  Tudo o que é imagem gerada (shields, stats, capsule) recebe essas cores por
  querystring, em vez de tema pronto. Mudou o portfólio, mude aqui.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,60:1e3a8a,100:3b82f6&height=160&section=header&text=Felipe%20Giacomini%20Cocco&fontColor=ededed&fontSize=38&fontAlignY=32&desc=back-end%20%C2%B7%20automation%20%C2%B7%20applied%20AI&descSize=16&descAlignY=52&descColor=93c5fd" width="100%" />

<a href="https://github.com/felipegco">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3600&pause=900&color=60A5FA&center=true&vCenter=true&width=640&lines=Back-end+developer+%E2%80%94+Java%2FSpring+Boot+and+Python;REST+APIs%2C+JWT%2C+JPA+and+relational+databases;Linux%2C+Docker+and+CI%2FCD+on+the+deploy+side;LLM+automations+with+n8n+%E2%80%94+in+production%2C+for+a+real+client;Open+to+junior+and+internship+roles" alt="Back-end developer — Java/Spring Boot and Python" />
</a>

<br/>

<!-- os três numa linha só do fonte: quebra de linha aqui vira badge empilhado no GitHub -->
<a href="https://felipegco.github.io/"><img src="https://img.shields.io/badge/Portfolio-felipegco.github.io-3b82f6?style=for-the-badge&labelColor=0a0a0a&logo=googlechrome&logoColor=60a5fa" alt="Portfolio" /></a> <a href="https://linkedin.com/in/felipegcocco"><img src="https://img.shields.io/badge/LinkedIn-felipegcocco-1e3a8a?style=for-the-badge&labelColor=0a0a0a&logo=linkedin&logoColor=60a5fa" alt="LinkedIn" /></a> <a href="mailto:fgiacominicocco@gmail.com"><img src="https://img.shields.io/badge/Email-fgiacominicocco-141416?style=for-the-badge&labelColor=0a0a0a&logo=maildotru&logoColor=60a5fa" alt="Email" /></a>

<img src="https://komarev.com/ghpvc/?username=felipegco&label=profile%20views&color=3b82f6&style=flat-square" alt="Profile views" />

</div>

<h3 align="center"><code>&gt;</code> about</h3>

**Back-end** with Java 17 + Spring Boot 3 and Python: REST APIs, Spring Security with JWT,
JPA/Hibernate, PostgreSQL and MariaDB. Docker and GitHub Actions on the deploy side.

**Almost 2 years in corporate IT** before writing code full time — Linux and Windows
servers, Active Directory, automation in Python/Bash/PowerShell, production incidents
traced from logs. It is why I think about logging, failure modes and deploy from the first
commit, not after the demo.

**Applied AI, shipped not demoed.** An LLM in production for a real client: free-text
classification with temperature 0, a safe default that escalates ambiguity to a human
instead of guessing, and a local-model fallback when the cloud API is down.

Information Systems @ FHO · graduating **Dec 2027** · 🇧🇷 Portuguese native, English B2
(technical reading and writing daily)

<h3 align="center"><code>&gt;</code> stack</h3>

<div align="center">

<sub>**back-end**</sub><br/>
<img src="https://skillicons.dev/icons?i=java,spring,maven,python,django,nodejs&theme=dark" alt="Java, Spring, Maven, Python, Django, Node.js" />

<sub>**data**</sub><br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,sqlite&theme=dark" alt="PostgreSQL, MySQL/MariaDB, Redis, SQLite" />

<sub>**infra & automation**</sub><br/>
<img src="https://skillicons.dev/icons?i=linux,docker,git,github,githubactions,bash&theme=dark" alt="Linux, Docker, Git, GitHub, GitHub Actions, Bash" />
<img height="48" src="https://img.shields.io/badge/n8n-0a0a0a?style=for-the-badge&logo=n8n&logoColor=60a5fa" alt="n8n" />
<img height="48" src="https://img.shields.io/badge/Ollama-0a0a0a?style=for-the-badge&logo=ollama&logoColor=60a5fa" alt="Ollama" />

<sub>**front-end & apps**</sub><br/>
<img src="https://skillicons.dev/icons?i=js,react,nextjs,tailwind,swift&theme=dark" alt="JavaScript, React, Next.js, Tailwind, Swift" />

</div>

<h3 align="center"><code>&gt;</code> selected work</h3>

<table>
<tr>
<th align="left" width="21%">project</th>
<th align="left">what it does</th>
<th align="left" width="27%">stack</th>
</tr>

<tr>
<td valign="top">
<b>WindFree</b><br/>
<sub>iOS + macOS · private</sub>
</td>
<td valign="top">
Native client for a Samsung AC over the SmartThings API, with Home Screen and Control
Center widgets plus Siri/Shortcuts intents. The interesting part is the plumbing:
<b>OAuth refresh serialised across processes</b> with a file lock so the app and its widget
extension never race, tokens written to Keychain before use and never logged, and commands
<b>verified by reading state back</b> — the API's <code>ACCEPTED</code> only means queued,
not applied.
</td>
<td valign="top">
<img src="https://img.shields.io/badge/Swift-0a0a0a?style=flat-square&logo=swift&logoColor=60a5fa" alt="Swift" />
<img src="https://img.shields.io/badge/SwiftUI-0a0a0a?style=flat-square&logo=swift&logoColor=60a5fa" alt="SwiftUI" />
<img src="https://img.shields.io/badge/App_Intents-0a0a0a?style=flat-square&logo=apple&logoColor=60a5fa" alt="App Intents" />
<img src="https://img.shields.io/badge/WidgetKit-0a0a0a?style=flat-square&logo=apple&logoColor=60a5fa" alt="WidgetKit" />
<img src="https://img.shields.io/badge/Keychain_%2B_OAuth-0a0a0a?style=flat-square&logo=auth0&logoColor=60a5fa" alt="Keychain + OAuth" />
</td>
</tr>

<tr>
<td valign="top">
<b>e-Move</b><br/>
<a href="https://e-move-frontend.vercel.app">live demo</a> ·
<a href="https://github.com/felipegco/e-move-backend">api</a> ·
<a href="https://github.com/felipegco/e-move-frontend">web</a>
</td>
<td valign="top">
Route planner for electric vehicles: virtual garage with 29+ models, range estimation,
charging stations along the way, trip history and CO₂ avoided. Two external APIs through
<code>WebClient</code> (LocationIQ, OpenChargeMap), JWT in an HttpOnly cookie, JUnit +
Mockito, containerised with CI on GitHub Actions. Started as a terminal app running
Dijkstra.
</td>
<td valign="top">
<img src="https://img.shields.io/badge/Java_17-0a0a0a?style=flat-square&logo=openjdk&logoColor=60a5fa" alt="Java 17" />
<img src="https://img.shields.io/badge/Spring_Boot_3-0a0a0a?style=flat-square&logo=springboot&logoColor=60a5fa" alt="Spring Boot 3" />
<img src="https://img.shields.io/badge/Spring_Security-0a0a0a?style=flat-square&logo=springsecurity&logoColor=60a5fa" alt="Spring Security" />
<img src="https://img.shields.io/badge/MariaDB-0a0a0a?style=flat-square&logo=mariadb&logoColor=60a5fa" alt="MariaDB" />
<img src="https://img.shields.io/badge/Docker-0a0a0a?style=flat-square&logo=docker&logoColor=60a5fa" alt="Docker" />
<img src="https://img.shields.io/badge/Next.js-0a0a0a?style=flat-square&logo=nextdotjs&logoColor=60a5fa" alt="Next.js" />
</td>
</tr>

<tr>
<td valign="top">
<b>WhatsApp scheduling assistant</b><br/>
<sub>client project · private</sub>
</td>
<td valign="top">
Replaced one-by-one manual confirmation at a dental clinic. An LLM classifies the
patient's free-text reply into <code>confirm / cancel / question / wait</code> and updates
the scheduling API. Redis debounce joins fragmented messages before classifying,
temperature 0, <b>ambiguity defaults to "question" and reaches a human</b> rather than
risking a wrong cancellation, and a local Llama 3.1 takes over when the cloud API fails.
Every error seen in a real conversation became an explicit rule in the prompt.
</td>
<td valign="top">
<img src="https://img.shields.io/badge/n8n-0a0a0a?style=flat-square&logo=n8n&logoColor=60a5fa" alt="n8n" />
<img src="https://img.shields.io/badge/Groq_API-0a0a0a?style=flat-square&logo=lightning&logoColor=60a5fa" alt="Groq API" />
<img src="https://img.shields.io/badge/Ollama_Llama_3.1-0a0a0a?style=flat-square&logo=ollama&logoColor=60a5fa" alt="Ollama / Llama 3.1" />
<img src="https://img.shields.io/badge/Redis-0a0a0a?style=flat-square&logo=redis&logoColor=60a5fa" alt="Redis" />
</td>
</tr>

<tr>
<td valign="top">
<b>CliniCare</b><br/>
<a href="https://github.com/felipegco/clinicare-backend">api</a> ·
<a href="https://github.com/felipegco/clinicare-frontend">web</a>
</td>
<td valign="top">
Appointment scheduling for a real dental clinic in Rio Claro/SP, documented with
OpenAPI/Swagger. It is the API the WhatsApp assistant above talks to.
</td>
<td valign="top">
<img src="https://img.shields.io/badge/Java_17-0a0a0a?style=flat-square&logo=openjdk&logoColor=60a5fa" alt="Java 17" />
<img src="https://img.shields.io/badge/Spring_Boot_3-0a0a0a?style=flat-square&logo=springboot&logoColor=60a5fa" alt="Spring Boot 3" />
<img src="https://img.shields.io/badge/OpenAPI-0a0a0a?style=flat-square&logo=swagger&logoColor=60a5fa" alt="OpenAPI" />
<img src="https://img.shields.io/badge/React-0a0a0a?style=flat-square&logo=react&logoColor=60a5fa" alt="React" />
</td>
</tr>

<tr>
<td valign="top">
<b>GreenTech ERP</b><br/>
<a href="https://github.com/felipegco/PI_III_2026TB_GreenTech_Backend">api</a> ·
<sub>team project</sub>
</td>
<td valign="top">
Agricultural management API: greenhouses, planting batches, harvests, stock, climate and
irrigation, with role-based access per job title. Full environment orchestrated by Docker
Compose.
</td>
<td valign="top">
<img src="https://img.shields.io/badge/Python-0a0a0a?style=flat-square&logo=python&logoColor=60a5fa" alt="Python" />
<img src="https://img.shields.io/badge/Django_REST-0a0a0a?style=flat-square&logo=django&logoColor=60a5fa" alt="Django REST" />
<img src="https://img.shields.io/badge/PostgreSQL_16-0a0a0a?style=flat-square&logo=postgresql&logoColor=60a5fa" alt="PostgreSQL 16" />
<img src="https://img.shields.io/badge/Docker_Compose-0a0a0a?style=flat-square&logo=docker&logoColor=60a5fa" alt="Docker Compose" />
</td>
</tr>
</table>

<sub>
Also around: <a href="https://github.com/felipegco/simple-notch"><b>Simple-Island</b></a>
— a deliberately minimal Dynamic Notch for macOS, born as a critique of the swiss-army-knife
alternatives ·
<a href="https://github.com/felipegco/port-scanner"><b>port-scanner</b></a>
— concurrent TCP scanner in Python, 50 threads, with an explicit responsible-use notice ·
<a href="https://github.com/felipegco/monitoramento-de-eficiencia-energetica"><b>energy dashboard</b></a>
— Next.js + shadcn/ui front-end for per-room consumption, on simulated data
</sub>

<h3 align="center"><code>&gt;</code> certifications & currently</h3>

<div align="center">

<img src="https://img.shields.io/badge/Red_Hat-Linux_Fundamentals_RH104-0a0a0a?style=for-the-badge&labelColor=0a0a0a&logo=redhat&logoColor=60a5fa" alt="Red Hat RH104" />
<img src="https://img.shields.io/badge/Cisco-Intro_to_Cybersecurity-0a0a0a?style=for-the-badge&labelColor=0a0a0a&logo=cisco&logoColor=60a5fa" alt="Cisco Introduction to Cybersecurity" />

<br/><br/>

<img src="https://img.shields.io/badge/learning-JUnit_5_%2B_Mockito_%2B_Testcontainers-3b82f6?style=flat-square&labelColor=0a0a0a" alt="Learning: JUnit 5, Mockito, Testcontainers" />
<img src="https://img.shields.io/badge/learning-AWS_Cloud_Practitioner-1e3a8a?style=flat-square&labelColor=0a0a0a" alt="Learning: AWS Cloud Practitioner" />

</div>

<h3 align="center"><code>&gt;</code> activity</h3>

<div align="center">

<!--
  Gerada por .github/workflows/snake.yml, na paleta do portfólio, e publicada na
  branch `output` deste repo. A action roda todo dia às 6h UTC e a cada push na main.
  Se as imagens quebrarem: aba Actions -> snake -> Run workflow.
  Sem a action rodar pelo menos uma vez, a branch `output` não existe e dá 404 —
  era o estado em que este README estava antes de 2026-11-04.
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/felipegco/felipegco/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/felipegco/felipegco/output/snake-light.svg" />
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/felipegco/felipegco/output/snake-dark.svg" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,40:1e3a8a,100:0a0a0a&height=120&section=footer" width="100%" />

<!--
  ─────────────────────────────────────────────────────────────────────────────
  Reserva: widgets de atividade, já na paleta do portfólio. Nenhum está em uso —
  a seção de atividade saiu inteira. Testar a URL no navegador antes de colar de
  volta: widget fora do ar vira imagem quebrada, que é pior que widget nenhum.

  Já descartados, e por quê:
  - ghchart.rshah.org: desenha os dias sem contribuição em branco, destoa do fundo.
  - github-readme-activity-graph: respondia HTTP 402 em 2026-11-04.

  <img align="right" width="390" src="https://github-readme-stats.vercel.app/api?username=felipegco&show_icons=true&hide_border=true&border_radius=12&bg_color=0a0a0a&title_color=60a5fa&text_color=ededed&icon_color=3b82f6&rank_icon=github" alt="GitHub stats" />

  <img height="168" src="https://github-readme-stats.vercel.app/api/top-langs/?username=felipegco&layout=compact&langs_count=8&hide_border=true&border_radius=12&bg_color=0a0a0a&title_color=60a5fa&text_color=ededed" alt="Most used languages" />

  E o card de streak, que funciona (demolab, no ar em 2026-11-04). Saiu porque expõe
  "current streak" — um número que fica feio em qualquer semana de prova:

  <img height="168" src="https://streak-stats.demolab.com?user=felipegco&hide_border=true&border_radius=12&background=0a0a0a&stroke=1e3a8a&ring=60a5fa&fire=60a5fa&currStreakNum=ededed&currStreakLabel=60a5fa&sideNums=ededed&sideLabels=a1a1aa&dates=a1a1aa" alt="Contribution streak" />
  ─────────────────────────────────────────────────────────────────────────────
-->
