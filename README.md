<!-- Dépôt à nommer exactement : Ronallogo -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Ron%20Allogo&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-stack%20%26%20IA%20%E2%80%A2%20Java%20%E2%80%A2%20Angular%20%E2%80%A2%20LangGraph&descAlignY=58&descSize=18" width="100%" alt="Bannière Ron Allogo" />

<a href="https://github.com/Ronallogo">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&height=50&lines=Salut+%F0%9F%91%8B+moi+c'est+Ron;D%C3%A9veloppeur+full-stack+%26+IA;Java+Spring+Boot+%E2%80%A2+Angular+%E2%80%A2+Python;Des+syst%C3%A8mes+qui+tournent+en+production;Pas+des+d%C3%A9mos+%F0%9F%9A%80" alt="Texte animé" />
</a>

<br/>

![Followers](https://img.shields.io/github/followers/Ronallogo?label=Followers&style=for-the-badge&color=36bcf7&labelColor=181717)
![Visiteurs](https://komarev.com/ghpvc/?username=Ronallogo&label=Visiteurs&color=36bcf7&style=for-the-badge&labelColor=181717)

<br/>

[**À propos**](#apropos) ·
[**En ce moment**](#encemoment) ·
[**Projets**](#projets) ·
[**Stack**](#stack) ·
[**Stats**](#stats) ·
[**Contact**](#contact)

</div>

---

<a id="apropos"></a>
## 👨‍💻 À propos

**Développeur full-stack & IA**, formé en Fullstack Java (Spring Boot + Angular) à SEED Institutes of Languages, avec l'École Supérieure de Gestion de l'Information et des Sciences.

Je conçois des **plateformes e-commerce multi-étapes**, des **agents IA autonomes** et des **outils de cybersécurité**.

> 🎯 **Mon obsession : des systèmes qui tournent pour de vrai, en production, pas des démos.**

---

<a id="encemoment"></a>
## 🔭 En ce moment

<table>
<tr>
<td width="33%" valign="top">

### 🛒 TITANMALL
Marketplace unifiée (marketplace, courses, immobilier, messagerie).
Backend **Spring Modulith** + applications **Angular**, déployés sur VPS.

</td>
<td width="33%" valign="top">

### 🤖 Agents IA
Passage de la démo à la production réelle : agents **LangGraph** avec garde-fous, scopes et preuves.

</td>
<td width="33%" valign="top">

### 🔐 CyberPentest
Plateforme de pentest autonome et orchestration d'agents de sécurité.

</td>
</tr>
</table>

---

<a id="projets"></a>
## 🏆 Projets phares

> 👇 Cliquez sur un bloc pour le déplier.

<details open>
<summary><b>🌐 Plateformes e-commerce : TITAN</b></summary>
<br/>

Le cœur de mon travail : une **plateforme e-commerce multi-métiers**, en architecture modulaire avec Domain-Driven Design.

| Projet | Rôle | Stack |
|---|---|---|
| **TITAN Core** | Socle backend unifié : modules `Market`, `food`, `immo`, `Coursier`, `Messagerie`. DDD, Spring Modulith, PostgreSQL, Redis, MinIO, WebSocket/STOMP | Java 17, Spring Boot 3.3, Gradle |
| **TITANMALL Hub** | Application Angular 21 : espaces client, marchand, admin, logisticien. Theme Builder, layouts drag & drop avec workflow draft/published + versioning, SEO par magasin | Angular 21, Tailwind 4, ApexCharts, STOMP |
| **Titan Tune Reset** | API de référence complète : auth JWT, upload MinIO, e-mails, OpenAPI, tests | Spring Boot, Spring Security, MinIO, JJWT, Thymeleaf |

**Points notables**
- 📐 Diagrammes UML + MCD + architecture documentés (PlantUML : contexte statique, use cases par acteur, séquences)
- 🚢 Déploiement multi-environnements : Docker Compose (dev / hub / prod), Nginx, migration VPS
- ⚡ MinIO / S3 pour le stockage objet, Elasticsearch, WebSocket temps réel pour la messagerie

</details>

<details open>
<summary><b>🤖 Agents IA & Cybersécurité</b></summary>
<br/>

| Projet | Description | Stack |
|---|---|---|
| **[agent_deezer](https://github.com/Ronallogo/agent_deezer)** | Agent de recherche musicale : trouve un titre, un artiste ou le top 10 d'un artiste. Outils Deep Agents sur l'API publique Deezer, tracing LangSmith | Python, Deep Agents, Groq, LangGraph |
| **CyberPentest-LangGraph** | Plateforme de pentest **en production réelle** (plus de simulation). Graphe `CERTIFY → EXECUTE → FINALIZE`, actions réseau réelles. Garde-fous : liste blanche de cibles, scopes R4–R7, prompt anti-hallucination, rapport PDF | Python, LangGraph, Groq |
| **CyberPentest-AI** | Version plateforme : orchestration d'agents, scan réseau / webscan, moteur de remédiation (génération de patchs + vérification), Elasticsearch, PDF, WebSocket | Java, Spring Boot, OpenRouter, Docker |
| **Trading Agent** | Agent d'analyse marchés (prix, volumes, sentiment) avec scoring VERT / ORANGE / ROUGE. **Bras d'exécution verrouillé** : `DRY_RUN` par défaut, plafonds codés en dur, confirmation explicite, interface WhatsApp (Twilio) | Python, LangGraph, MT5, Twilio |

> 🛡️ **Principe commun à mes agents :** jamais d'action irréversible sans mandat explicite, jamais de résultat sans preuve.

</details>

<details>
<summary><b>📱 Applications mobiles & Java</b></summary>
<br/>

- **Bumaye App** : application Android en Kotlin (Gradle KTS)
- **login_kotlin** : authentification mobile Kotlin
- **Employee Management** : gestion d'employés, full-stack (Angular + Spring Boot)
- **Scierie** : gestion de scierie, full-stack (Angular + Spring Boot)
- **SIG** : Système d'Information Géographique, full-stack
- **Agence de Voyage** : réservation de voyages, full-stack
- **Restaurant "Oasis de douceur"** : gestion de restaurant (JavaFX + Spring Boot + Angular)

</details>

<details>
<summary><b>🎨 Frontend & design</b></summary>
<br/>

- **Portfolio** : site vitrine React 19 + Vite + Tailwind 4 + Material Tailwind
- **Design Patterns (Java)** : patterns State & co., application JavaFX

</details>

<details>
<summary><b>📂 Autres dépôts (exercices et apprentissage)</b></summary>
<br/>

`Algorithme_C` · `ALGORITHME` · `Design_Pattern_State_Implementation` · `data_science` · `projectClientBeginner` · `APP_SPORT` · `projectRestaurant` · `python_function` · `first`

</details>

---

<a id="stack"></a>
## 🛠 Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,gradle,maven,py,angular,react,ts,tailwind,vite,kotlin,androidstudio,postgres,redis,elasticsearch,docker,nginx,git,linux&perline=10" alt="Technologies" />

</div>

<details>
<summary><b>👉 Voir le détail par domaine</b></summary>
<br/>

| Domaine | Technologies |
|---|---|
| **Backend** | Java 17 · Spring Boot 3 · Spring Modulith · Spring Security · Spring Data JPA · Gradle · Maven · Hibernate |
| **IA & Data** | Python · LangGraph · Deep Agents · Groq · OpenRouter · Elasticsearch · PostgreSQL |
| **Frontend** | Angular 18/19/21 · React 19 · TypeScript · Tailwind CSS · Vite · ApexCharts |
| **Mobile** | Kotlin · Android SDK · Gradle KTS |
| **Infra & outils** | Docker · Docker Compose · Nginx · MinIO · Redis · STOMP/WebSocket · Git · Linux · Twilio |

</details>

<details>
<summary><b>📊 Ce que mes projets montrent</b></summary>
<br/>

| Domaine | Détails |
|---|---|
| 🏗️ **Architecture** | DDD, Spring Modulith, clean architecture, séparation domain / application / infrastructure |
| 🛡️ **Sécurité** | JWT, RBAC, validation, protection anti-hallucination, garde-fous d'exécution |
| 🚢 **Production** | Docker multi-stage, VPS, migrations SQL, déploiement reproductible |
| 📐 **Rigueur** | Tests unitaires, documentation d'architecture, diagrammes UML / PlantUML |
| 🤖 **IA** | Orchestration multi-agents, outils outillés, traçabilité, vérification des résultats |

</details>

---

<a id="stats"></a>
## 📈 Stats GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Ronallogo&show_icons=true&theme=tokyonight&hide_border=true&border_radius=12&count_private=false" alt="Stats GitHub" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ronallogo&layout=compact&theme=tokyonight&hide_border=true&border_radius=12" alt="Langages les plus utilisés" />

<br/>

<img src="https://streak-stats.demolab.com?user=Ronallogo&theme=tokyonight&hide_border=true&border_radius=12" alt="Série de contributions" />

</div>

---

<a id="contact"></a>
## 📫 Me contacter

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ronallogo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ron-allogo-070677293/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ronallogo45@gmail.com)

<br/>

💬 **Discutons** d'architecture, d'agents IA en production, de pentest, ou d'un projet que vous construisez.

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="" />

</div>
