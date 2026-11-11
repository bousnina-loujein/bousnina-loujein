<p align="center">
  <img src="assets/banner.svg" alt="Loujein Bousnina, Full-Stack IoT Engineer at RondeGuard. An ESP32 routes traces to firmware, cloud, dashboard and mobile." width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/loujein-bousnina/"><img src="https://img.shields.io/badge/LinkedIn-loujein--bousnina-123F36?style=for-the-badge&logo=linkedin&logoColor=D9B45A&labelColor=0C2E27" alt="LinkedIn" /></a>
  <a href="mailto:majdoub.loujein1211@gmail.com"><img src="https://img.shields.io/badge/Email-Write%20to%20me-123F36?style=for-the-badge&logo=gmail&logoColor=D9B45A&labelColor=0C2E27" alt="Email" /></a>
</p>

I build connected products from the copper up. At **RondeGuard** I own the whole chain: the ESP32 terminal and its PCB, the secure MQTT link, the Node.js backend, the supervisor dashboard and the agent app. I graduated from **ESPRIT** in 2026 with a National Engineering Degree in Ambient and Mobile Embedded Systems (SLEAM).

## What I'm building

### RondeGuard
Security patrol traceability: guards scan NFC checkpoints on their rounds, and supervisors follow every round live. It started as my end-of-studies project at Maker Skills and now runs in production.

<p align="center">
  <img src="assets/rondeguard.svg" alt="RondeGuard architecture: field terminal to EMQX broker to Node.js API and MongoDB, feeding the React dashboard and the Flutter agent app." width="100%" />
</p>

Under the hood: TLS credentials stored in ESP32 NVS, GSM fallback through a SIM800L, man-down detection from an MPU6050, and an agent app that keeps working offline.

### FireTrack
A RondeGuard product for fire extinguisher management: inventory, NFC and barcode-verified inspections, due-date tracking, defect reports and a digital fire safety log. Built with MongoDB, Express, React and Node in TypeScript.

## Selected projects

| Project | What it does | Built with |
|:--|:--|:--|
| **SNCFT train tracking**<br/><sub>Internship at SNCFT, 2025</sub> | Real-time GPS localization of trains, from a custom antenna to the passenger app. Split across [app](https://github.com/bousnina-loujein/SNCFT-Tracker), [dashboard](https://github.com/bousnina-loujein/sncft-web-dashboard), [API](https://github.com/bousnina-loujein/sncft-backend-api), [firmware](https://github.com/bousnina-loujein/sncft-iot-testing), [PCB](https://github.com/bousnina-loujein/sncft-pcb-design), [antenna](https://github.com/bousnina-loujein/sncft_AntenneGps_CST) and [model](https://github.com/bousnina-loujein/sncft-smart-model). | ESP32, Node-RED, NestJS, Flutter, TensorFlow, CST |
| **[Smart Health Glove](https://github.com/bousnina-loujein/smart_health_glove_mobileApp)**<br/><sub>ESPRIT, 2025</sub> | A sensor glove for rehabilitation, with a custom antenna and an app that visualizes hand movement in real time. | C++, embedded sensors, mobile |
| **WaterSec**<br/><sub>ESPRIT integrated project, 2025</sub> | Leak and contamination detection for water networks. LSTM models reached 85% accuracy and cut water waste by about 30% in lab tests. | ESP32, GSM, custom PCB, LSTM, Flutter |

## Toolbox

<p>
  <b>Hardware and firmware</b><br/>
  <img src="https://img.shields.io/badge/ESP32-123F36?style=flat-square&logo=espressif&logoColor=D9B45A" alt="ESP32" />
  <img src="https://img.shields.io/badge/STM32-123F36?style=flat-square&logo=stmicroelectronics&logoColor=D9B45A" alt="STM32" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-123F36?style=flat-square&logo=cplusplus&logoColor=D9B45A" alt="C/C++" />
  <img src="https://img.shields.io/badge/Arduino-123F36?style=flat-square&logo=arduino&logoColor=D9B45A" alt="Arduino" />
  <img src="https://img.shields.io/badge/Altium%20Designer-123F36?style=flat-square&logo=altiumdesigner&logoColor=D9B45A" alt="Altium Designer" />
  <img src="https://img.shields.io/badge/NFC%20%2F%20RFID-123F36?style=flat-square" alt="NFC / RFID" />
</p>

<p>
  <b>Connectivity</b><br/>
  <img src="https://img.shields.io/badge/MQTT-123F36?style=flat-square&logo=mqtt&logoColor=D9B45A" alt="MQTT" />
  <img src="https://img.shields.io/badge/EMQX-123F36?style=flat-square" alt="EMQX" />
  <img src="https://img.shields.io/badge/Node--RED-123F36?style=flat-square&logo=nodered&logoColor=D9B45A" alt="Node-RED" />
  <img src="https://img.shields.io/badge/Firebase-123F36?style=flat-square&logo=firebase&logoColor=D9B45A" alt="Firebase" />
</p>

<p>
  <b>Backend, web and mobile</b><br/>
  <img src="https://img.shields.io/badge/Node.js-123F36?style=flat-square&logo=nodedotjs&logoColor=D9B45A" alt="Node.js" />
  <img src="https://img.shields.io/badge/NestJS-123F36?style=flat-square&logo=nestjs&logoColor=D9B45A" alt="NestJS" />
  <img src="https://img.shields.io/badge/TypeScript-123F36?style=flat-square&logo=typescript&logoColor=D9B45A" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-123F36?style=flat-square&logo=react&logoColor=D9B45A" alt="React" />
  <img src="https://img.shields.io/badge/Flutter-123F36?style=flat-square&logo=flutter&logoColor=D9B45A" alt="Flutter" />
  <img src="https://img.shields.io/badge/MongoDB-123F36?style=flat-square&logo=mongodb&logoColor=D9B45A" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Spring%20Boot-123F36?style=flat-square&logo=springboot&logoColor=D9B45A" alt="Spring Boot" />
</p>

<p>
  <b>Deployment</b><br/>
  <img src="https://img.shields.io/badge/Docker-123F36?style=flat-square&logo=docker&logoColor=D9B45A" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-123F36?style=flat-square&logo=nginx&logoColor=D9B45A" alt="Nginx" />
  <img src="https://img.shields.io/badge/Linux-123F36?style=flat-square&logo=linux&logoColor=D9B45A" alt="Linux" />
  <img src="https://img.shields.io/badge/Jenkins-123F36?style=flat-square&logo=jenkins&logoColor=D9B45A" alt="Jenkins" />
</p>

## Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bousnina-loujein&show_icons=true&count_private=true&hide_border=true&border_radius=14&bg_color=123F36&title_color=D9B45A&text_color=F2F0E6&icon_color=C98A4B" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bousnina-loujein&layout=compact&hide_border=true&border_radius=14&bg_color=123F36&title_color=D9B45A&text_color=F2F0E6" alt="Top languages" />
</p>
