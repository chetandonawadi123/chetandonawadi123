<!-- ============================ HEADER ============================ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,60:0B2A4A,100:1F6FEB&height=230&section=header&text=Chetan%20Donawadi&fontSize=54&fontColor=E6EDF3&fontAlignY=40&desc=Backend%20Engineer%20%7C%20Cloud%20%7C%20Distributed%20%26%20Real-Time%20Systems&descAlignY=62&descSize=17&descColor=8B949E" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=760&height=40&lines=%3E+building+scalable+backend+systems;%3E+streaming+pipelines+with+Kafka+%26+Spark;%3E+cloud-native+on+AWS;%3E+IoT+security+%2B+machine+learning;%3E+open+to+backend+engineering+roles" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/chetan-donawadi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:chetandonawadi@gmail.com"><img src="https://img.shields.io/badge/Email-1F6FEB?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/AWS-Certified_Cloud_Practitioner-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900" />
<img src="https://img.shields.io/badge/Status-Open_to_Work-2EA043?style=flat-square" />
<img src="https://komarev.com/ghpvc/?username=chetandonawadi123&label=Views&color=1F6FEB&style=flat-square" />

</div>

<br/>

<!-- ============================ TERMINAL ============================ -->
```bash
chetan@dev:~$ whoami
Chetan Donawadi — Backend Engineer

chetan@dev:~$ cat profile.json
{
  "education"     : "B.Tech Computer Science, PES University (2026)",
  "certification" : "AWS Certified Cloud Practitioner (CLF-C02)",
  "focus"         : ["Backend Systems", "Streaming Pipelines", "Cloud", "IoT Security"],
  "languages"     : ["Python", "Java", "SQL"],
  "status"        : "Open to full-time backend roles"
}

chetan@dev:~$ _
```

<br/>

<!-- ============================ IMPACT ============================ -->
<div align="center">

![Accuracy](https://img.shields.io/badge/Model_Accuracy-90.67%25-1F6FEB?style=for-the-badge)
![Projects](https://img.shields.io/badge/Major_Projects-4-1F6FEB?style=for-the-badge)
![Hackathon](https://img.shields.io/badge/Hackathon-Top_10_of_52-1F6FEB?style=for-the-badge)
![GPA](https://img.shields.io/badge/Diploma_GPA-9.3%2F10-1F6FEB?style=for-the-badge)

</div>

<br/>

## Tech Stack

<table>
<tr>
<td width="25%" align="center"><b>Languages</b></td>
<td>
<img src="https://skillicons.dev/icons?i=py,java,mysql&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><b>Backend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=spring,flask,fastapi&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><b>Data & Streaming</b></td>
<td>
<img src="https://skillicons.dev/icons?i=kafka,spark,postgres,mysql&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><b>Cloud & DevOps</b></td>
<td>
<img src="https://skillicons.dev/icons?i=aws,docker,linux,git&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><b>ML & Robotics</b></td>
<td>
<img src="https://skillicons.dev/icons?i=tensorflow,py&theme=dark" />
<img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white" height="48" />
</td>
</tr>
<tr>
<td align="center"><b>Core CS</b></td>
<td>
<code>Data Structures & Algorithms</code> · <code>OOP</code> · <code>DBMS</code> · <code>Design Patterns</code> · <code>REST API Design</code>
</td>
</tr>
</table>

<br/>

## Selected Work

### FirmPot — Intelligent IoT Honeypot
`Python` `QEMU` `Reinforcement Learning` `AWS EC2` `S3` &nbsp;·&nbsp; *Research Project, Jan – May 2026*

Emulates OpenWrt firmware images with QEMU to create realistic embedded-device environments for threat observation. A modular pipeline (booter, scanner, learner) boots firmware, scans web interfaces, and learns interaction patterns. Reinforcement learning models attacker behavior to increase honeypot engagement and the quality of captured telemetry. Instances run on AWS EC2, with logs stored in S3 for vulnerability analysis.

```mermaid
flowchart LR
    A[OpenWrt Firmware] --> B[Booter / QEMU]
    B --> C[Scanner]
    C --> D[RL Learner]
    D --> E[Honeypot Instance on EC2]
    E --> F[(Telemetry in S3)]
    F --> G[Attack Log Analysis]
```

<br/>

### Predictive Maintenance of Medical Equipment
`Python` `Kafka` `TensorFlow` `AWS` &nbsp;·&nbsp; *December 2025*

A real-time system that predicts equipment failures, failure types, and severity from streaming sensor data, reaching **90.67% accuracy** with SVM and ANN models. MedGAN generates realistic synthetic data to overcome limited real-world datasets. A live dashboard provides monitoring, anomaly detection, and automated failure alerts.

```mermaid
flowchart LR
    S[Medical Sensors] --> K[Apache Kafka]
    K --> P[Stream Processing]
    P --> M[SVM / ANN Models]
    G[MedGAN Synthetic Data] -.-> M
    M --> D[Live Dashboard]
    M --> A[Failure Alerts]
```

<br/>

### Budget & Expense Tracker
`Java` `Spring Boot` `MySQL` `Spring Data JPA` &nbsp;·&nbsp; *September 2025*

A full-stack Spring Boot MVC application for expense tracking, budget planning, goal management, alerts, charts, and CSV export. Designed with OOAD principles and the **Strategy, Observer, Singleton, and DAO** patterns, with normalized MySQL persistence and unit-tested core services.

<br/>

### Hector SLAM Mapping & Indoor Positioning Robot
`ROS` `LiDAR` `Gazebo` `RViz` &nbsp;·&nbsp; *April 2025*

An autonomous indoor robot that builds accurate 2D occupancy grid maps in real time using only LiDAR, with no GPS, wheel odometry, or IMU. Scan-matching localization estimates robot pose in unknown environments, with ROS and RViz visualization and support for saving and reusing maps.

<br/>

## Achievements

| | |
|---|---|
| **AWS Certified Cloud Practitioner** | CLF-C02, May 2026 |
| **PESU Arithamania Hackathon** | Ranked Top 10 out of 52 teams |
| **Diploma in Mechatronics** | 9.3 / 10 GPA, Top 5% of batch |
| **AWS Cloud & Big Data** | Hands-on training |
| **Table Tennis** | State-level player |

<br/>

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=chetandonawadi123&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&bg_color=0D1117" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chetandonawadi123&layout=compact&hide_border=true&langs_count=8&title_color=58A6FF&text_color=C9D1D9&bg_color=0D1117" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=chetandonawadi123&hide_border=true&background=0D1117&ring=1F6FEB&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" />

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=chetandonawadi123&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=E6EDF3&area=true&area_color=1F6FEB&hide_border=true" />

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chetandonawadi123/chetandonawadi123/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chetandonawadi123/chetandonawadi123/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/chetandonawadi123/chetandonawadi123/output/github-snake-dark.svg" />
</picture>

</div>

<br/>

## Currently

- Building backend and cloud projects with a focus on clean architecture and reliability
- Going deeper into distributed systems and event-driven design
- Looking for a **full-time backend engineering role**

<br/>

<div align="center">

**Let's connect**

<a href="https://www.linkedin.com/in/chetan-donawadi"><img src="https://img.shields.io/badge/LinkedIn-chetan--donawadi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:chetandonawadi@gmail.com"><img src="https://img.shields.io/badge/chetandonawadi@gmail.com-1F6FEB?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,60:0B2A4A,100:1F6FEB&height=110&section=footer" width="100%" />
