<div align="center">

<h1>🎓 HiveMQ Edge</h1>
### Self-Paced Training Course · MQTT · Edge · Protocol Adapters

[![Tool](https://img.shields.io/badge/Tool-HiveMQ_Edge_(Open_Source)-FF6900?style=for-the-badge)](https://www.hivemq.com/hivemq-edge/)
[![Membership](https://img.shields.io/badge/Membership-FREE-4CAF50?style=for-the-badge)](#-module-1--basic)
[![Lessons](https://img.shields.io/badge/Lessons-9-FF9800?style=for-the-badge)](#-module-1--basic)
[![Videos](https://img.shields.io/badge/Videos_Ready-5-9C27B0?style=for-the-badge)](#-module-1--basic)

*Learn to install and run HiveMQ Edge on Windows, Linux and Docker, configure Protocol Adapters (OPC-UA, Modbus TCP) and bridge your shop-floor data to any MQTT broker — one short lesson at a time.*

<p align="center">
  <a href="https://www.hivemq.com/releases/hivemq-edge-latest.zip"><img src="https://img.shields.io/badge/Download_HiveMQ_Edge-FF6900?style=for-the-badge&logo=hivemq&logoColor=white" alt="Download HiveMQ Edge"></a>
  <a href="https://www.oracle.com/in/java/technologies/downloads/#jdk21-windows"><img src="https://img.shields.io/badge/Download_Java_JDK_21-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Download Java"></a>
</p>

<br>

<p align="center">
  <a href="https://www.youtube.com/@Fusion_Automate"><img src="https://img.shields.io/badge/YouTube-FusionAutomate-%23FF0000?style=for-the-badge&logo=youtube" alt="YouTube"></a>
  <a href="https://www.instagram.com/fusion_automate"><img src="https://img.shields.io/badge/Instagram-fusion__automate-%23E4405F?style=for-the-badge&logo=instagram" alt="Instagram"></a>
  <a href="https://x.com/fusion_automate"><img src="https://img.shields.io/badge/X-fusion__automate-000000?style=for-the-badge&logo=x" alt="X (Twitter)"></a>
  <a href="https://t.me/fusionautomate"><img src="https://img.shields.io/badge/Telegram-%40fusionautomate-%2326A5E4?style=for-the-badge&logo=telegram" alt="Telegram"></a>
  <a href="https://fusionautomate.in/"><img src="https://img.shields.io/badge/Website-fusionautomate.in-blueviolet?style=for-the-badge" alt="Website"></a>
</p>

</div>

**Legend:** 🆓 Free lesson · ✅ Video available · ⌛ In progress / coming soon

---

## 📘 Module 1 · Basic

| # | Lesson | Watch |
|:-:|--------|:-----:|
| 1 | 🆓 Intro to HiveMQ Edge Architecture | [![Watch](https://img.shields.io/badge/▶_Watch-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/KFWCOGpTt6U) |
| 2 | 🆓 Install HiveMQ Edge on Windows | [![Watch](https://img.shields.io/badge/▶_Watch-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/UOQnRKgJnBg) |
| 3 | Install HiveMQ Edge on Raspberry Pi | ⌛ |
| 4 | Install HiveMQ Edge on Linux (VirtualLabs) | ⌛ |
| 5 | 🆓 Run HiveMQ Edge in Docker (VirtualLabs) | [![Watch](https://img.shields.io/badge/▶_Watch-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/jlxbcqCDhjo) |

<details>
<summary>📋 Raspberry Pi install commands</summary>

```bash
wget https://www.hivemq.com/releases/hivemq-edge-latest.zip
unzip hivemq-edge-latest.zip
sudo add-apt-repository ppa:openjdk-r/ppa
sudo apt-get update && sudo apt-get upgrade -y
sudo apt install openjdk-21-jre
bash run.sh
```
</details>

<details>
<summary>📋 Linux (VirtualLabs) install commands</summary>

```bash
wget https://www.hivemq.com/releases/hivemq-edge-latest.zip
unzip hivemq-edge-latest.zip
sudo dnf install java-21-amazon-corretto
bash run.sh
```
</details>

<details>
<summary>📋 Docker run command</summary>

```bash
docker run --name hivemq-edge -d -p 1883:1883 -p 8080:8080 hivemq/hivemq-edge
```
</details>

---

## 📘 Module 2 · Protocol Adapter

| # | Lesson | Watch |
|:-:|--------|:-----:|
| 1 | 🆓 Configure OPC-UA → MQTT Adapter | [![Watch](https://img.shields.io/badge/▶_Watch-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/jFFr-L1u6fM) |
| 2 | Configure Modbus TCP Adapter | ⌛ |

---

## 📘 Module 3 · MQTT Bridge

| # | Lesson | Watch |
|:-:|--------|:-----:|
| 1 | 🆓 MQTT Bridge · Stream OPC-UA Data to MQTT Broker | [![Watch](https://img.shields.io/badge/▶_Watch-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/b_H2F7ZvjMU) |
| 2 | MQTT Bridge · Stream Modbus TCP Device Data | ⌛ |

---

<h1 align="center">📢 Reach Out to Us for Any Queries ⤵️</h1>

<table align="center">
  <thead>
    <tr>
      <th>📞 Contact Method</th>
      <th>🔗 Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Call / WhatsApp</td>
      <td><a href="https://wa.me/919974477759">+91-9974477759</a></td>
    </tr>
    <tr>
      <td>Telegram</td>
      <td><a href="https://t.me/fusionautomate">@fusionautomate</a></td>
    </tr>
    <tr>
      <td>Email</td>
      <td><a href="mailto:eng.innovativ@gmail.com">eng.innovativ@gmail.com</a></td>
    </tr>
  </tbody>
</table>

---

<div align="center">

✨ **Enjoying these lessons? Support our work!** ✨

<a href="https://buymeacoffee.com/pylin" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="40">
</a>

<a href="https://www.youtube.com/channel/UCKKhdFV0q8CV5vWUDfiDfTw" target="_blank">
  <img src="https://raw.githubusercontent.com/papercodeIN/HiveMQ-Edge/main/assets/youtube-subscribe.png" alt="Subscribe on YouTube" height="40">
</a>

</div>
