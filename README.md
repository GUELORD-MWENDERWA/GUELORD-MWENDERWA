# Guelord Mwenderwa

**Embedded Systems and AI Engineer** · Goma, DR Congo

I build systems that go from the sensor to the decision: electronics and firmware on the device, the data pipeline and machine learning model behind it, and the web platform people use to operate it. My background combines hands-on electronics training with a computer science degree in artificial intelligence, and my work sits where the two meet: access control, energy monitoring, building automation, predictive maintenance and business platforms.

I publish my work as open source, with tests and documentation, and teach embedded programming and full-stack web development.

[LinkedIn](https://linkedin.com/in/guelord-mwenderwa) · [Email](mailto:guelsmwenderwa@gmail.com)

---

## Education

| Institution | Program |
| --- | --- |
| **ISIG Goma**, Institut Supérieur d'Informatique et de Gestion | Licence in Computer Science, Artificial Intelligence track (LSI-IA), currently in second year |
| **ITIG Don Bosco**, Institut Technique Industriel de Goma | Technical diploma in General Electronics |

---

## Areas of expertise

| Domain | Scope |
| --- | --- |
| Embedded systems | Arduino (AVR), ESP32, ESP8266, STM32; modular C++ firmware, state machines, non-blocking scheduling, ADC sampling, EEPROM/NVS persistence, OTA |
| Electronics | Analog and digital circuit design, power supplies, sensors, measurement, circuit simulation |
| Control systems | Discrete PID with anti-windup and derivative filtering, motor control |
| Machine learning | Classical ML and neural networks from first principles, feature engineering for signals and images, embedded inference (TinyML) |
| Mathematics for engineering | Numerical analysis, statistics and hypothesis testing, linear algebra |
| Backend and data | Python, Django, Django REST Framework; Node.js, Express, Prisma; PostgreSQL, relational modelling |
| Front end | React, TypeScript, Vite, Tailwind CSS |
| Systems and networks | Operating system algorithms, IPv4 design and routing |

---

## Open source

Libraries and tools with tests, CI and documentation. Each implements its subject from first principles and is validated against reference results.

### Artificial intelligence and data

| Project | Description |
| --- | --- |
| [edge-ai-motor-fault-detector](https://github.com/GUELORD-MWENDERWA/edge-ai-motor-fault-detector) | Motor fault diagnosis from current signatures with a 172-parameter neural network running on an ESP32. Python training, C++ export, and a parity test proving the firmware matches the model |
| [ml-from-scratch](https://github.com/GUELORD-MWENDERWA/ml-from-scratch) | Linear models, CART trees, k-NN, k-means, PCA and an MLP with manual backpropagation and gradient checking, in NumPy only |
| [statistics-from-scratch](https://github.com/GUELORD-MWENDERWA/statistics-from-scratch) | Distributions, confidence intervals, t, chi-square and ANOVA tests, regression inference; incomplete gamma and beta functions implemented and validated against SciPy |
| [numerical-analysis-toolkit](https://github.com/GUELORD-MWENDERWA/numerical-analysis-toolkit) | Root finding, interpolation, quadrature, Runge-Kutta ODE solvers, direct and iterative linear solvers, with convergence-order tests |
| [PROJET-TUTORE-LSI-IA-L1](https://github.com/GUELORD-MWENDERWA/PROJET-TUTORE-LSI-IA-L1) | Geometric shape recognition: contour features, Hu moments, Random Forest and a desktop application |

### Electronics and embedded systems

| Project | Description |
| --- | --- |
| [circuit-solver](https://github.com/GUELORD-MWENDERWA/circuit-solver) | SPICE-like simulator using modified nodal analysis: DC operating point, AC sweep and backward-Euler transient |
| [esp32-web-oscilloscope](https://github.com/GUELORD-MWENDERWA/esp32-web-oscilloscope) | Browser-based oscilloscope: 50 kS/s sampling, edge trigger with pre-trigger history, Vpp, Vrms, frequency and duty cycle |
| [dc-motor-pid-controller](https://github.com/GUELORD-MWENDERWA/dc-motor-pid-controller) | Closed-loop motor speed control with a PID library unit-tested against a motor model |
| [arduino-component-tester](https://github.com/GUELORD-MWENDERWA/arduino-component-tester) | Auto-ranging resistance, capacitance from RC timing, and diode identification |
| [electronics-toolkit](https://github.com/GUELORD-MWENDERWA/electronics-toolkit) | Design calculator: colour codes, E-series, dividers, NE555, op-amps, zener regulators, rectifiers |
| [logic-circuit-toolkit](https://github.com/GUELORD-MWENDERWA/logic-circuit-toolkit) | Boolean expression parser, Quine-McCluskey minimisation with don't-cares, gate-level simulation of adders |

### Systems, networks and databases

| Project | Description |
| --- | --- |
| [os-scheduling-simulator](https://github.com/GUELORD-MWENDERWA/os-scheduling-simulator) | CPU scheduling with Gantt charts, page replacement including Belady's anomaly, Banker's algorithm, disk scheduling |
| [ipv4-network-toolkit](https://github.com/GUELORD-MWENDERWA/ipv4-network-toolkit) | Subnetting, VLSM, route summarisation, longest-prefix match and link-state routing |
| [academic-records-database](https://github.com/GUELORD-MWENDERWA/academic-records-database) | 3NF academic records schema with credit-weighted averages and resits, portable across SQLite and PostgreSQL |

---

## Connected systems

### Computer Lab Automation
[SYSTEME_DOMOTIQUE-_SALLE-_NFORMATIQUE](https://github.com/GUELORD-MWENDERWA/SYSTEME_DOMOTIQUE-_SALLE-_NFORMATIQUE) · ESP32, C++17

Dual-reader RFID access with occupancy counting, PZEM-004T energy metering, daylight-aware lighting, night-time intrusion detection and eight switched loads, operated from a web dashboard, a REST API and a serial console.

### SGIS: School Management Information System
[sgis-v2](https://github.com/GUELORD-MWENDERWA/sgis-v2) · Django REST Framework, JWT, PostgreSQL

School administration API with attendance recorded by QR code, by ESP32 RFID terminals authenticated with module tokens, or manually.

### Access control
[smart-door-rfid_arduino](https://github.com/GUELORD-MWENDERWA/smart-door-rfid_arduino) · [CONTROLE_ACCES_CAPTEUR_BIOMETRIQUE](https://github.com/GUELORD-MWENDERWA/CONTROLE_ACCES_CAPTEUR_BIOMETRIQUE)

An RFID and keypad door controller built on an explicit state machine with a desktop companion application, and a fingerprint access controller with a REST API and web dashboard.

### 433 MHz RF remote control
[Transmitter](https://github.com/GUELORD-MWENDERWA/emeteur_433mhz_rf-interrupteur_4_pos_arduino_code) · [Receiver](https://github.com/GUELORD-MWENDERWA/recepteur_433mhz_rf-interrupteur_4_pos_arduino_code)

Four-channel remote with sequence-numbered frames, burst retransmission, duplicate suppression, and toggle, momentary and timed relay modes.

---

## Teaching

| Course | Content |
| --- | --- |
| [FORMATION-PROGRAMMATION-EMBARQUER](https://github.com/GUELORD-MWENDERWA/FORMATION-PROGRAMMATION-EMBARQUER) | Embedded C++ fundamentals on Arduino, one concept per exercise |
| [FORMATION-PYTHON-DJANGO](https://github.com/GUELORD-MWENDERWA/FORMATION-PYTHON-DJANGO) | Full-stack path from HTML and CSS to a deployed Django application |

---

## Professional work

I build and maintain private business platforms for organisations in the region: monorepo applications with a React and TypeScript front end, an Express and Prisma API on PostgreSQL, role-based access control, client portals, PDF reporting and real-time updates.

---

## Engineering practice

- **Verify against a reference.** Numerical code is checked against analytical results or established libraries; firmware logic is unit-tested on the host before it reaches hardware.
- **Keep the maths visible.** Algorithms are implemented from first principles when the goal is understanding, and documented with their assumptions and limits.
- **Design hardware and software together.** Pin maps, protocols and data models are specified before code is written.
- **State limits honestly.** Each project says what has been validated and what has not.

---

## Tech stack

**Embedded and electronics**
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Espressif](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white)

**AI and data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Backend and web**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Tooling**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=guelord-mwenderwa&theme=default&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=guelord-mwenderwa&theme=default&hide_border=true&layout=compact&langs_count=8" alt="Most used languages" />
</p>
