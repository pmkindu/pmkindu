# Hi there, I'm Prince 👋

### Mechatronics Engineer | Embedded Systems, CAN Bus & Test Automation

Mechatronics Engineer (M.Eng.) with hands-on experience in test engineering, measurement technology and software testing. I build embedded and IoT systems and secure them with automated tests and CI pipelines using Python, C++, Docker, AWS and Linux.

---

## 🛠️ Tech Stack & Tools

- **Languages:** Python, C/C++, Bash, HTML5/CSS3
- **Embedded & IoT:** ESP32-S3, ESP8266 (NodeMCU), Arduino Nano, PlatformIO, I²C/SPI sensors and displays, hardware-software integration
- **Automotive & Bus Systems:** CAN bus (MCP2515/TJA1050, 500 kbit/s), DBC files, python-can, cantools, CANable 2.0
- **DevOps & Cloud:** GitHub Actions (CI/CD), Docker, Docker Compose, AWS (ECS, ECR)
- **Test Automation & QA:** Pytest, Behave (Gherkin BDD), REST API testing, unit testing, HAL/hardware mocking
- **Environment & Tools:** Linux (Ubuntu/WSL2), Git, VS Studiio Code, Postman

---

## 🚀 Featured Portfolio Projects

1. **[CAN-Guard](https://github.com/pmkindu/CAN-Guard)** 🚧 *in development*
   - Distributed CAN bus sensor network with five nodes at 500 kbit/s: four Arduino Nano sensor nodes (switch/LDR, ultrasonic, 3× DHT11, motion) and an ESP32-S3 gateway.
   - **Firmware:** C++ / PlatformIO with MCP2515 controllers, diagnostic frames per node, timeout monitoring and a fallback mode when a sensor message is lost.
   - **Network spec:** DBC file as single source of truth for all messages and signals.
   - **CI/CD & QA:** Test-first GitHub Actions pipeline that checks the DBC against the specification with Pytest, cantools and python-can (virtual bus); hardware tests planned with a CANable 2.0 adapter.
   - **Planned:** gateway with touch display, rotary encoder and web dashboard.

2. **[WeatherPulse-IoT](https://github.com/pmkindu/WeatherPulse-IoT)**
   - End-to-end IoT outdoor weather monitoring & real-time plausibility validation system.
   - **Firmware:** ESP8266 (C++ / PlatformIO) reading DHT20 sensor & driving SH1106 OLED over I²C.
   - **Backend & Cloud:** FastAPI REST service integrated with Open-Meteo API, dockerized and deployed to **AWS ECS**.
   - **CI/CD & QA:** Fully automated GitHub Actions workflow executing PlatformIO build checks & **Pytest** test suite (12/12 passing).

3. **[iot-medtech-distance-alert](https://github.com/pmkindu/iot-medtech-distance-alert)**
   - Automated BDD test suite & CI/CD pipeline for an IoT MedTech Distance Alert System.
   - Built using FastAPI, Docker Compose, Behave (Gherkin BDD), and GitHub Actions.

4. **[Python API Test Suite & BDD Framework](https://github.com/pmkindu/python-api-test-suite)** [![Run Python API & BDD Tests](https://github.com/pmkindu/python-api-test-suite/actions/workflows/test.yml/badge.svg)](https://github.com/pmkindu/python-api-test-suite/actions)
   - Automated REST API testing framework using Python, Pytest, and Gherkin BDD scenarios.
   - Fully integrated with GitHub Actions CI pipeline.

5. **[Dockerized Test Environment](https://github.com/pmkindu/docker-test-environment)** [![MedTech BDD Integration Tests](https://github.com/pmkindu/docker-test-environment/actions/workflows/test.yml/badge.svg)](https://github.com/pmkindu/docker-test-environment/actions)
   - Containerized BDD testing setup designed for regulated environments (ISO 13485 / FDA CFR Title 21 Part 11).
   - Automated orchestration with Docker Compose, PostgreSQL 15, Behave, and GitHub Actions CI.

6. **[Linux System Diagnostics & Log Parser](https://github.com/pmkindu/linux-system-diagnostics)** [![CI Status](https://github.com/pmkindu/linux-system-diagnostics/actions/workflows/test.yml/badge.svg)](https://github.com/pmkindu/linux-system-diagnostics/actions)
   - Automated Bash scripting suite for CPU, RAM, Disk monitoring and system log parsing (`ERROR` patterns).
   - Fully integrated with GitHub Actions CI.

---

## 📫 Connect with Me

- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/princemvutikindu/)
- **XING:** [XING Profile](https://www.xing.com/profile/Prince_MvutiKindu/web_profiles)