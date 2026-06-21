cat > /mnt/user-data/outputs/README.md << 'ENDOFFILE'
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:00D4FF,100:8A2BE2&height=200&section=header&text=SIVANESH%20G&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Embedded%20Systems%20%7C%20Semiconductor%20%7C%20IoT%20%7C%20AI&descAlignY=58&descSize=18&animation=fadeIn"/>

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=2500&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&repeat=true&width=750&height=50&lines=⚡+Aspiring+Semiconductor+%26+Embedded+Engineer;🔬+Building+Real-World+Embedded+Solutions;🤖+ESP32+%7C+BLE+%7C+IoT+%7C+AI+%7C+C%2B%2B;🎓+2nd+Year+ECE+%40+SRM+Easwari+Engineering" alt="Typing SVG" />

</div>

<br>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sivaneshg)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sivaneshgnanasekar183@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sivanesh-ECE)
[![Profile Views](https://komarev.com/ghpvc/?username=Sivanesh-ECE&color=00D4FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Sivanesh-ECE)

</div>

<br>

---

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="25"> `./whoami`

<table>
<tr>
<td width="55%" valign="top">

```c
/**
 * @file    sivanesh.h
 * @version 2.0-ECE
 * @brief   Embedded Engineer in the Making
 */

#include <passion.h>
#include <embedded_systems.h>
#include <semiconductor.h>
#include <never_stop_learning.h>

typedef struct Engineer {

  const char *name     = "Sivanesh G";
  const char *status   = "2nd Year ECE Student";
  const char *college  = "SRM Easwari Engineering College";
  const char *location = "Tamil Nadu, India";
  const char *target   = "Semiconductor & Embedded Roles";

  const char *stack[]  = {
    "C", "C++", "Arduino",
    "ESP32", "Arduino Uno",
    "BLE", "I2C", "I2S",
    "Arduino IDE", "GitHub"
  };

  bool open_to_intern      = true;
  bool loves_hardware      = true;
  bool currently_learning  = "VLSI + RTOS";

} Sivanesh_G;

// Mission: Build smarter embedded futures
```

</td>
<td width="45%" valign="top">

<img src="https://github-readme-stats.vercel.app/api?username=Sivanesh-ECE&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=00D4FF&text_color=C9D1D9&count_private=true" width="100%"/>

<br>

<img src="https://nirzak-streak-stats.vercel.app/?user=Sivanesh-ECE&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D4FF&ring=00D4FF&fire=FF6B35&currStreakLabel=00D4FF" width="100%"/>

</td>
</tr>
</table>

---

## ⚡ Tech Stack & Arsenal

<div align="center">

### 〔 Programming Languages 〕
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)

### 〔 Embedded Platforms 〕
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino Uno](https://img.shields.io/badge/Arduino_Uno-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![MPU6050](https://img.shields.io/badge/MPU6050_IMU-FF4500?style=for-the-badge&logoColor=white)

### 〔 Communication Protocols 〕
![BLE](https://img.shields.io/badge/Bluetooth_LE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)
![I2C](https://img.shields.io/badge/I2C-FF6B35?style=for-the-badge&logoColor=white)
![I2S](https://img.shields.io/badge/I2S_Audio-8A2BE2?style=for-the-badge&logoColor=white)
![GPIO](https://img.shields.io/badge/GPIO-228B22?style=for-the-badge&logoColor=white)

### 〔 Tools & Integrations 〕
![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-008184?style=for-the-badge&logo=arduino&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps_API-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 🔬 Featured Projects

<div align="center">

> 🛠️ *Three builds. Three real-world problems solved. All from 1st year.*

</div>

<br>

### 🖱️ `PROJECT_01` — Bluetooth Air Mouse using ESP32

<table>
<tr>
<td width="50%">

```
 ┌──────────────────────────────────────┐
 │           SIGNAL FLOW                │
 │                                      │
 │  [MPU6050]──►[ESP32]──BLE──►[PC]    │
 │   6-axis       FW      HID  cursor   │
 │   gyro+acc   gesture  profile click  │
 │                                      │
 │  Latency: <10ms    Range: ~10m       │
 └──────────────────────────────────────┘
```

</td>
<td width="50%">

**🎯 Problem:** Hands-free wireless mouse control<br>
**⚙️ Stack:** ESP32 · MPU6050 · BLE HID · C++<br>
**💡 Key Win:** Real-time 6-axis gesture-to-cursor mapping<br>
**🏁 Impact:** Zero-contact HCI via air motion sensing

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![BLE](https://img.shields.io/badge/BLE_HID-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</td>
</tr>
</table>

---

### 🪖 `PROJECT_02` — Smart Helmet for Rider Safety

<table>
<tr>
<td width="50%">

**🎯 Problem:** Delayed emergency response in accidents<br>
**⚙️ Stack:** ESP32 · IMU · GPS · Google Maps · IoT<br>
**💡 Key Win:** Auto SOS on crash — zero manual action<br>
**🏁 Impact:** Real-time GPS alert to emergency contacts

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-00C7B7?style=flat-square&logoColor=white)
![GPS](https://img.shields.io/badge/GPS-4285F4?style=flat-square&logo=googlemaps&logoColor=white)

</td>
<td width="50%">

```
 ┌──────────────────────────────────────┐
 │           CRASH PIPELINE             │
 │                                      │
 │  [IMU]──►[ESP32]──►[GPS]            │
 │  detect    MCU      coords           │
 │              │                       │
 │              └──►[SOS]──►[Contact]   │
 │                  WiFi    Emergency   │
 │                           auto-ping  │
 └──────────────────────────────────────┘
```

</td>
</tr>
</table>

---

### 🤖 `PROJECT_03` — AI Voice Assistant using ESP32

<table>
<tr>
<td width="50%">

```
 ┌──────────────────────────────────────┐
 │           VOICE PIPELINE             │
 │                                      │
 │  [I2S Mic]──►[Wake Engine]──►[MCU]  │
 │   audio in    offline detect  ESP32  │
 │                                  │   │
 │                     ┌────────────┘   │
 │                     ▼                │
 │  [OpenAI]◄──[WiFi]──►[I2S Speaker]  │
 │   cloud LLM              audio out   │
 └──────────────────────────────────────┘
```

</td>
<td width="50%">

**🎯 Problem:** Embedded AI without full cloud dependency<br>
**⚙️ Stack:** ESP32 · I2S Mic · Speaker · OpenAI API<br>
**💡 Key Win:** Hybrid offline wake + cloud NLP pipeline<br>
**🏁 Impact:** Hands-free IoT control from microcontroller

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![I2S](https://img.shields.io/badge/I2S-8A2BE2?style=flat-square&logoColor=white)

</td>
</tr>
</table>

---

## 🏆 Achievement Log

<div align="center">

<table>
<tr>
<td align="center" width="33%">

🏅<br>
**VIT Technical Quiz**<br><br>
Won an **iPad** in Technical Quiz Competition by VIT<br><br>
`2024`

</td>
<td align="center" width="33%">

🥇<br>
**Academic Excellence**<br><br>
Trophy + Cash Prize for **Maths, Physics & Chemistry**<br><br>
`2024`

</td>
<td align="center" width="33%">

⚡<br>
**Project Builder**<br><br>
Shipped multiple **Embedded + IoT** projects as a 1st year student<br><br>
`2023–24`

</td>
</tr>
</table>

</div>

---

## 📡 Skill Radar — Currently Calibrating

<div align="center">

| Domain | Level | Status |
|:-------|:-----:|:------:|
| `Embedded Systems` | ████████████░░░ 80% | 🟢 Active |
| `C / C++` | ███████████░░░░ 72% | 🟢 Active |
| `IoT & Wireless` | ██████████░░░░░ 66% | 🟢 Active |
| `Circuit Design` | ████████░░░░░░░ 55% | 🟡 Growing |
| `VLSI Design` | █████░░░░░░░░░░ 32% | 🟡 Learning |
| `AI / ML` | ████░░░░░░░░░░░ 28% | 🔵 Exploring |
| `Semiconductor` | ████░░░░░░░░░░░ 25% | 🔵 Exploring |

</div>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sivanesh-ECE&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=C9D1D9" width="45%"/>

<img src="https://github-profile-trophy.vercel.app/?username=Sivanesh-ECE&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=4" width="50%"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sivanesh-ECE&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=00D4FF&line=00D4FF&point=FFFFFF&area=true" width="100%"/>

</div>

---

## 🔗 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20Connect!-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sivaneshg)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-Drop%20a%20Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sivaneshgnanasekar183@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-Follow%20My%20Work-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sivanesh-ECE)

</div>

---

<div align="center">

```c
/* main.c — the loop that never ends */

void loop() {
    absorb(knowledge);
    design(circuits);
    flash(firmware);
    debug(everything);
    ship(projects);
    repeat();          // always
}
```

<br>

> ⚡ *"I don't just study electronics — I build with it."*

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,50:00D4FF,100:0D1117&height=120&section=footer&animation=fadeIn"/>

</div>
ENDOFFILE
echo "Done
