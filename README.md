<div align="center">

```
███████╗██╗██╗   ██╗ █████╗ ███╗   ██╗███████╗███████╗██╗  ██╗    ██████╗
██╔════╝██║██║   ██║██╔══██╗████╗  ██║██╔════╝██╔════╝██║  ██║   ██╔════╝
███████╗██║██║   ██║███████║██╔██╗ ██║█████╗  ███████╗███████║   ██║  ███╗
╚════██║██║╚██╗ ██╔╝██╔══██║██║╚██╗██║██╔══╝  ╚════██║██╔══██║   ██║   ██║
███████║██║ ╚████╔╝ ██║  ██║██║ ╚████║███████╗███████║██║  ██║   ╚██████╔╝
╚══════╝╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝╚═╝  ╚═╝    ╚═════╝
```

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=⚡+Embedded+Systems+%7C+Semiconductor+%7C+IoT+%7C+AI;🔬+ECE+Student+%40+SRM+Easwari+Engineering+College" alt="Typing SVG" />

</div>

---

<table>
<tr>
<td width="60%" valign="top">

## `whoami`

```c
/* sivanesh.h — v2.0-ECE */

#include <passion.h>
#include <embedded_systems.h>
#include <semiconductor.h>

typedef struct {
    char   *name       = "Sivanesh G";
    char   *role       = "ECE Student (2nd Year)";
    char   *college    = "SRM Easwari Engineering College";
    char   *location   = "Tamil Nadu, India";

    char   *languages[]  = {"C", "C++", "Arduino"};
    char   *platforms[]  = {"ESP32", "Arduino Uno"};
    char   *protocols[]  = {"BLE", "I2C", "I2S"};
    char   *tools[]      = {"Arduino IDE", "GitHub"};

    char   *mission = "Build smarter embedded futures";
    bool    open_to_collaborate = true;
} Sivanesh;
```

</td>
<td width="40%" valign="top">

## `./stats`

<img src="https://github-readme-stats.vercel.app/api?username=sivaneshg&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=00D4FF&text_color=C9D1D9" width="100%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sivaneshg&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D4FF&ring=00D4FF&fire=FF6B35&currStreakLabel=00D4FF" width="100%"/>

</td>
</tr>
</table>

---

## ⚡ SIGNAL FLOW — My Build Arsenal

<div align="center">

| 🔵 CORE | 🟠 HARDWARE | 🟢 PROTOCOLS | ⚪ TOOLS |
|:-------:|:-----------:|:------------:|:--------:|
| ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) | ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white) | ![BLE](https://img.shields.io/badge/BLE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white) | ![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white) |
| ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) | ![Arduino](https://img.shields.io/badge/Arduino_Uno-00979D?style=for-the-badge&logo=arduino&logoColor=white) | ![I2C](https://img.shields.io/badge/I2C-FF6B35?style=for-the-badge&logoColor=white) | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) |
| ![Arduino](https://img.shields.io/badge/Arduino_Lang-00979D?style=for-the-badge&logo=arduino&logoColor=white) | ![MPU6050](https://img.shields.io/badge/MPU6050-FF4500?style=for-the-badge&logoColor=white) | ![I2S](https://img.shields.io/badge/I2S_Audio-8A2BE2?style=for-the-badge&logoColor=white) | ![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white) |

</div>

---

## 🔬 PROJECT SCHEMATIC

> *Three builds. Three real-world problems solved.*

<details open>
<summary><b>🖱️ PROJECT_01 — BLUETOOTH AIR MOUSE (ESP32 + MPU6050)</b></summary>

<br>

```
[MPU6050 IMU] ──► [ESP32 MCU] ──BLE──► [HOST COMPUTER]
  6-axis gyro        firmware            HID Mouse Profile
  accel data         gesture map         cursor + click
```

- 🎯 **Problem:** Hands-free wireless control without hardware buttons
- ⚙️ **Stack:** ESP32 · MPU6050 · BLE HID Protocol · C++
- 💡 **Key Win:** Real-time motion-to-cursor mapping via gesture thresholding
- 🏁 **Impact:** Improved HCI through zero-contact, air-gesture interaction

<br>
</details>

---

<details>
<summary><b>🪖 PROJECT_02 — SMART HELMET FOR RIDER SAFETY (ESP32 + IoT)</b></summary>

<br>

```
[Motion Sensor] ──► [ESP32] ──► [GPS Module] ──► [Google Maps API]
  crash detect        MCU           coords             route track
                       │
                       └──► [SOS Alert] ──► [Emergency Contact]
                                GSM/WiFi        auto-trigger
```

- 🎯 **Problem:** Delayed emergency response after road accidents
- ⚙️ **Stack:** ESP32 · Motion Sensors · GPS · Google Maps · IoT
- 💡 **Key Win:** Automated SOS dispatch on crash event — zero manual input
- 🏁 **Impact:** Real-time accident monitoring + emergency notification pipeline

<br>
</details>

---

<details>
<summary><b>🤖 PROJECT_03 — AI VOICE ASSISTANT (ESP32 + OpenAI)</b></summary>

<br>

```
[I2S Mic] ──► [Wake Word Engine] ──► [ESP32] ──► [OpenAI NLP API]
  audio in        offline detect       MCU           language model
                                        │
                                        └──► [I2S Speaker] ──► [IoT Devices]
                                               audio out          smart ctrl
```

- 🎯 **Problem:** Embedded voice AI without cloud dependency for wake detection
- ⚙️ **Stack:** ESP32 · I2S · OpenAI API · Offline Wake-word Engine
- 💡 **Key Win:** Hybrid offline/online architecture — local wake, cloud inference
- 🏁 **Impact:** Hands-free voice control for IoT devices + real-time Q&A

<br>
</details>

---

## 🏆 ACHIEVEMENT LOG

```
[2024] ████████████████████ VIT Technical Quiz — WON iPad 🏆
[2024] ████████████████     Trophy + Cash Prize — Maths, Physics, Chemistry 🥇  
[2024] ████████████         Multiple Embedded & IoT Projects Shipped as 1st Year ⚡
```

---

## 📡 FREQUENCY SPECTRUM — Areas Exploring

<div align="center">

```
LOW FREQ ◄─────────────────────────────────────────► HIGH FREQ

[VLSI Design] [Semiconductors] [Embedded] [IoT] [Robotics] [AI/ML]
     ████           █████         ██████   █████    ███       ████
   Exploring      Exploring      ██ NOW ██  NOW    Learning  Learning
```

</div>

---

## 📊 LANGUAGE ACTIVITY

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sivaneshg&layout=donut&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=C9D1D9" />
</div>

---

## 🔗 ESTABLISH CONNECTION

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sivaneshg)
[![Gmail](https://img.shields.io/badge/Gmail-Mail_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sivaneshgnanasekar183@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sivaneshg)

</div>

---

<div align="center">

```
/* Always compiling. Always debugging. Always shipping. */

while (student) {
    learn();
    build();
    iterate();
}
```

![Profile Views](https://komarev.com/ghpvc/?username=sivaneshg&color=00D4FF&style=for-the-badge&label=PROFILE+VIEWS)

⚡ *"The best embedded systems are the ones nobody notices — because they just work."*

</div>

