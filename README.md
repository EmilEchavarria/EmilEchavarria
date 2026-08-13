<img src="./header.svg" width="100%" alt="Emil Echavarria — Junior Systems Engineer at Giro Credito. Ships mobile, web, and backend." />

<br/>

<a href="https://emilechavarria.vercel.app"><img src="https://img.shields.io/badge/Portfolio-emilechavarria.vercel.app-64FFDA?style=flat&logo=vercel&logoColor=64FFDA&labelColor=0d1117" alt="Portfolio" /></a>
&nbsp;
<a href="https://linkedin.com/in/emil-echavarria"><img src="https://img.shields.io/badge/LinkedIn-emil--echavarria-0A66C2?style=flat&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn" /></a>
&nbsp;
<a href="mailto:emilechavarria2005@gmail.com"><img src="https://img.shields.io/badge/Email-emilechavarria2005@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email" /></a>
&nbsp;
<img src="https://img.shields.io/badge/Location-York%2C%20PA-8892b0?style=flat&labelColor=0d1117" alt="York, PA" />
<img src="https://img.shields.io/badge/Work-U.S.%20Authorized-64FFDA?style=flat&labelColor=0d1117" alt="U.S. Work Authorized" />

---

<table>
<tr>
<td width="58%" valign="top">

### Now

**Junior Systems Engineer** at **Giro Crédito** — fintech, remote from Santo Domingo. I ship production features across the **mobile app**, **web portal**, and **backend**.

Capstone: 6-service medical platform with applied ML and OpenAI. 2nd place at **AlphaRamos** with SirenaMap (ESP32 indoor navigation).

ITLA · GPA 3.8/4.0 · Graduating Oct 2026  
Spanish (native) · English (intermediate) · No sponsorship required

</td>
<td width="42%" valign="top">

<img src="https://github-readme-stats.vercel.app/api?username=EmilEchavarria&show_icons=true&hide_title=true&hide_border=true&theme=transparent&bg_color=00000000&title_color=64FFDA&icon_color=64FFDA&text_color=8892b0&ring_color=64FFDA" alt="GitHub stats" />

</td>
</tr>
</table>

---

### Systems I ship

How production work is split at Giro — clients, API, jobs, and data.

```mermaid
flowchart LR
  A[Mobile · React Native / Expo] --> API[Django + Django Ninja]
  W[Web · Next.js] --> API
  API --> PG[(PostgreSQL)]
  API --> Q[Celery]
  Q --> R[(Redis)]
  API --> CH[WhatsApp / Push / SMS / Email]
