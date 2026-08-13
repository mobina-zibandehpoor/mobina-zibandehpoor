<!-- Profile theme: path · signal · motion -->

<p align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Eyes.png" alt="eyes" width="48" height="48" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Compass.png" alt="compass" width="48" height="48" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Woman%20Walking.png" alt="walking" width="48" height="48" />
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3200&pause=900&color=0F766E&center=true&vCenter=true&width=720&lines=Mobina+Zibandehpoor;reading+how+people+find+their+way" alt="typing" />
</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:14B8A6,100:99F6E4&height=140&section=header&text=&fontSize=0&animation=fadeIn" width="100%" alt="wave" />
</p>

<p align="center">
  <b>M.Sc. Mechatronics</b> · Biomechatronics Lab · K. N. Toosi University of Technology<br/>
  <i>she/her</i> · non-invasive cognitive assessment through movement, gaze & sensor fusion
</p>

<p align="center">
  <a href="https://mobina-zibandehpoor.github.io/"><img src="https://img.shields.io/badge/-portfolio-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="portfolio" /></a>
  <a href="mailto:mobinazibandeh@gmail.com"><img src="https://img.shields.io/badge/-email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://www.linkedin.com/in/mobina-zibandehpoor/"><img src="https://img.shields.io/badge/-linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="https://scholar.google.com/citations?user=_-slqcUAAAAJ&hl=en"><img src="https://img.shields.io/badge/-scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="scholar" /></a>
  <a href="https://orcid.org/0009-0003-2355-5383"><img src="https://img.shields.io/badge/-orcid-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="orcid" /></a>
</p>

<br/>

## the idea

I study **how humans navigate space** — and how we can measure that ability without invasive tools.

My work sits between **mechatronics**, **computer vision**, and **cognitive science**. In the lab I build pipelines that turn everyday signals — walking trajectories, head motion, eye movements — into indices that say something real about spatial memory and sense of direction.

Thesis focus: a non-invasive framework using **vision-based pose estimation** + **IMU motion capture**, with ML for feature extraction and interpretability. Parallel track: **EOG eye tracking** during the Leiden Navigation Test.

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2800&pause=1200&color=64748B&center=true&vCenter=true&width=680&lines=pose+%E2%86%92+IMU+%E2%86%92+EOG+%E2%86%92+features+%E2%86%92+cognitive+index;low-burden+sensing+%C2%B7+interpretable+models+%C2%B7+open+data" alt="pipeline typing" />
</p>

<br/>

## how I think about a study

```text
          ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
   walk → │   cameras   │ ──▸ │   RTMPose   │ ──▸ │ trajectory  │
          │   + IMUs    │     │  / OpenPose │     │  + joints   │
          └─────────────┘     └─────────────┘     └──────┬──────┘
                                                         │
          ┌─────────────┐     ┌─────────────┐            ▼
   gaze → │     EOG     │ ──▸ │ blinks ·    │     ┌─────────────┐
          │  H / V ch.  │     │ saccades ·  │ ──▸ │  multimodal │
          └─────────────┘     │ fixations   │     │  classifier │
                              └─────────────┘     └─────────────┘
```

<br/>

## what I've been building

<table>
<tr>
<td width="50%" valign="top">

### open data
**[EOG · Leiden Navigation Test](https://github.com/mobina-zibandehpoor/EOG-LNT-Spatial-Navigation-Dataset)**  
27 healthy participants · vertical & horizontal EOG during LNT  
→ published in *Nature Scientific Data*

### motion pipelines
**[MoWalCT · RTMPose trajectories](https://github.com/mobina-zibandehpoor/MoWalCT-RTMPose-trajectory-extraction)**  
Walking Corsi paths, extracted & cleaned

**[MoWalCT · head / trunk angles](https://github.com/mobina-zibandehpoor/MoWalCT-head-trunk-cleaned-joint-angles)**  
joint-angle cleaning for WalCT analysis

</td>
<td width="50%" valign="top">

### gaze & vision
**[L2CS-Net gaze detection](https://github.com/mobina-zibandehpoor/L2CS-Net-Gaze-Detection)**  
video gaze estimation · L2CS-Net + Gaze360

### geometry
**[Brain 3D CAD models](https://github.com/mobina-zibandehpoor/Brain-3D-Cad-Model)**  
human brain models for biomechatronics work

### writing home
**[Academic portfolio](https://mobina-zibandehpoor.github.io/)**  
papers, experience, and notes

</td>
</tr>
</table>

<br/>

## papers that matter most to me right now

| year | venue | note |
|:----:|:------|:-----|
| 2025 | *Scientific Data* (Nature) | EOG dataset for objective spatial navigation assessment |
| 2026 | IEEE ICWR | multimodal sense-of-direction from trajectory + head motion |
| 2025 | CSICC | eye-movement biometrics in navigation · **Best Paper** |
| 2024 | ICRoM | WalCT trajectory assessment via pose estimation |
| 2024 | arXiv | Persian Wayfinding Questionnaire |

<p align="center">
  <a href="https://scholar.google.com/citations?user=_-slqcUAAAAJ&hl=en">full scholar list →</a>
  &nbsp;·&nbsp;
  <a href="https://orcid.org/0009-0003-2355-5383">orcid →</a>
  &nbsp;·&nbsp;
  <a href="https://www.researchgate.net/profile/Mobina-Zibandehpoor">researchgate →</a>
</p>

<br/>

## path so far

```mermaid
timeline
    title education & research
    2017–2021 : B.Sc. Electrical Eng. (Telecom) · University of Zanjan
               : Top student · IoT weather-station thesis
    2022–2025 : M.Sc. Mechatronics · K. N. Toosi
               : Spatial navigation from movement patterns
               : Supervisor — Dr. Mehdi Delrobaei
    now       : Research · teaching · peer review
               : Open datasets & WalCT / EOG pipelines
```

<br/>

## toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,matlab,cpp,opencv,pytorch,sklearn,git,linux,latex&theme=light" alt="skills" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/pose-RTMPose%20%2F%20OpenPose-0F766E?style=flat-square" />
  <img src="https://img.shields.io/badge/signals-EOG%20%2F%20IMU-14B8A6?style=flat-square" />
  <img src="https://img.shields.io/badge/ML-interpretable%20%2F%20XAI-0D9488?style=flat-square" />
  <img src="https://img.shields.io/badge/stats-SPSS%20%2F%20G*Power-5EEAD4?style=flat-square" />
  <img src="https://img.shields.io/badge/writing-LaTeX%20%2F%20Jupyter-99F6E4?style=flat-square" />
</p>

<br/>

## milestones

<p align="center">
  <img src="https://img.shields.io/badge/%F0%9F%8F%86_Best_Paper-CSICC_2025-C2410C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/%F0%9F%8F%86_Best_Thesis_Nominee-IEEE_Iran_Section-B45309?style=for-the-badge" />
</p>

- 3rd place — 3-Minute Thesis & 3-Minute Article (K. N. Toosi)
- Best seminar — Electrical Engineering Faculty (2024)
- 3rd place — Best Bachelor's Thesis in IoT (national, 2022)
- TA — Biomechatronic Systems & Neuromuscular Control Systems
- Peer reviewer — IEEE Access · Int. Journal of Web Research · MEAAC

<br/>

## activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mobina-zibandehpoor&bg_color=ffffff&color=0f766e&line=14b8a6&point=0d9488&area=true&hide_border=true&custom_title=contribution%20rhythm" width="100%" alt="activity graph" />
</p>

<p align="center">
  <img height="158" src="https://github-readme-stats.vercel.app/api?username=mobina-zibandehpoor&show_icons=true&include_all_commits=true&hide_border=true&title_color=0F766E&icon_color=14B8A6&text_color=334155&bg_color=FFFFFF00" alt="stats" />
  <img height="158" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mobina-zibandehpoor&layout=compact&hide_border=true&title_color=0F766E&text_color=334155&bg_color=FFFFFF00&langs_count=6" alt="langs" />
</p>

<br/>

## say hello

I'm open to collaborations on **spatial cognition**, **HCI**, **biosignals**, and **AI for behavioral assessment**.

<p align="center">
  <a href="mailto:mobinazibandeh@gmail.com">
    <img src="https://img.shields.io/badge/write_me-mobinazibandeh%40gmail.com-0F766E?style=for-the-badge&logo=gmail&logoColor=white" alt="mail" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:99F6E4,50:14B8A6,100:0F766E&height=100&section=footer&animation=fadeIn" width="100%" alt="footer wave" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=4000&pause=1000&color=94A3B8&center=true&vCenter=true&width=520&lines=thanks+for+finding+your+way+here" alt="bye" />
</p>
