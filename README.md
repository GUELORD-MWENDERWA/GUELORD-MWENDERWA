# Guelord Mwenderwa

**Embedded Systems and Full-Stack Engineer**, based in Goma, DR Congo.

I design connected systems end to end: the electronics and firmware on the device, the backend that receives its data, and the web interfaces people use to operate it. My work focuses on access control, attendance, energy monitoring and building automation, along with business web platforms and applied machine learning.

I also teach embedded programming and full-stack web development, and publish the course material openly.

[LinkedIn](https://linkedin.com/in/guelord-mwenderwa) · [Email](mailto:guelsmwenderwa@gmail.com)

---

## Areas of expertise

| Domain | Scope |
| --- | --- |
| Embedded systems | Arduino (AVR), ESP32, ESP8266, STM32; modular C++ firmware, finite state machines, non-blocking scheduling, EEPROM/NVS persistence, OTA updates |
| IoT and connectivity | Wi-Fi, HTTP/REST on the device, asynchronous web servers, 433 MHz RF, UART, SPI, I2C |
| Access control and identification | RFID (MFRC522), fingerprint sensors, keypad authentication, relay and door strike control |
| Backend engineering | Python, Django, Django REST Framework, JWT; Node.js, Express, Prisma; PostgreSQL |
| Front end | React, TypeScript, Vite, Tailwind CSS; HTML, CSS, JavaScript |
| Machine learning | Feature engineering for computer vision, scikit-learn pipelines, OpenCV, NumPy, pandas |
| Delivery | Git, CI, PlatformIO, Render, Firebase, environment-based configuration |

---

## Selected projects

### Computer Lab Automation System
[SYSTEME_DOMOTIQUE-_SALLE-_NFORMATIQUE](https://github.com/GUELORD-MWENDERWA/SYSTEME_DOMOTIQUE-_SALLE-_NFORMATIQUE) · ESP32, C++17, PlatformIO

Building controller combining dual-reader RFID access with occupancy counting, PZEM-004T energy metering, daylight-aware lighting, night-time intrusion detection and eight switched loads. Operated from a web dashboard, a REST API and a serial console. Firmware split into eleven independent modules.

### SGIS: School Management Information System
[sgis-v2](https://github.com/GUELORD-MWENDERWA/sgis-v2) · Django REST Framework, JWT, PostgreSQL

REST API for school administration: users and roles, school years, classes, students, and attendance recorded by QR code, by ESP32 RFID terminals authenticated with module tokens, or manually. Deployable to Render.

### Smart Door Controller
[smart-door-rfid_arduino](https://github.com/GUELORD-MWENDERWA/smart-door-rfid_arduino) · Arduino Mega, C++, Python

Access control built around an explicit finite state machine: RFID badges stored in EEPROM, PIN-protected administration from a keypad, JSON serial protocol, and a companion desktop application (CustomTkinter GUI and CLI).

### Biometric Access Control
[CONTROLE_ACCES_CAPTEUR_BIOMETRIQUE](https://github.com/GUELORD-MWENDERWA/CONTROLE_ACCES_CAPTEUR_BIOMETRIQUE) · ESP32, ESPAsyncWebServer

Fingerprint enrollment and identification with a REST API, a web dashboard served from SPIFFS, a queued serial command interface, and local LCD, LED and buzzer feedback.

### Geometric Shape Recognition
[PROJET-TUTORE-LSI-IA-L1](https://github.com/GUELORD-MWENDERWA/PROJET-TUTORE-LSI-IA-L1) · Python, OpenCV, scikit-learn, PyQt5

Classical computer vision pipeline classifying seven shapes: synthetic data generation, contour-based feature engineering with Hu moments, Random Forest classifier, evaluation and a desktop application. Includes ten guided exercises.

### 433 MHz RF Remote Control
[Transmitter](https://github.com/GUELORD-MWENDERWA/emeteur_433mhz_rf-interrupteur_4_pos_arduino_code) · [Receiver](https://github.com/GUELORD-MWENDERWA/recepteur_433mhz_rf-interrupteur_4_pos_arduino_code) · Arduino, RadioHead

Four-channel remote with sequence-numbered frames, burst retransmission and duplicate suppression. The receiver maps buttons to relays with toggle, momentary and timed modes.

---

## Teaching material

| Course | Content |
| --- | --- |
| [FORMATION-PROGRAMMATION-EMBARQUER](https://github.com/GUELORD-MWENDERWA/FORMATION-PROGRAMMATION-EMBARQUER) | Embedded C++ fundamentals on Arduino, one concept per exercise |
| [FORMATION-PYTHON-DJANGO](https://github.com/GUELORD-MWENDERWA/FORMATION-PYTHON-DJANGO) | Full-stack path from HTML and CSS to a deployed Django application |

---

## Professional work

I build and maintain private business platforms for organisations in the region: monorepo applications with a React and TypeScript front end, an Express and Prisma API on PostgreSQL, role-based access control, client portals, PDF reporting and real-time updates. These repositories are private.

---

## How I work

- **Hardware and software designed together**: pin maps, protocols and data models are specified before code is written.
- **Explicit state**: firmware is built around state machines and non-blocking loops rather than delays.
- **Documented interfaces**: every device that talks to a server ships with its protocol or API reference.
- **Production habits in small projects**: environment-based configuration, migrations, reproducible builds.

---

## Tech stack

**Embedded**
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Espressif](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white)

**Backend and web**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Machine learning**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Tooling**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

---

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=guelord-mwenderwa&theme=default&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=guelord-mwenderwa&theme=default&hide_border=true&layout=compact&langs_count=8" alt="Most used languages" />
</p>
