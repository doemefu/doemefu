# Hi, I'm Dominic 👋

Software engineer with a background spanning embedded systems, enterprise Java, and mission-critical financial software. I bridge the gap between hardware and cloud — from microcontroller firmware to OAuth 2.1 microservices deployed on Kubernetes.

Currently studying **B.Sc. Software Systems** at the University of Zurich, with a minor in Business Administration.

---

## 🔌 What I Build

My main focus is **IoT systems** — end-to-end, from the sensor to the dashboard. The Terra1 project is a good example: an ESP32 microcontroller reads temperature, humidity, soil moisture, and light data, publishes it over MQTT, and feeds into a Spring Boot microservices backend with JWT-secured APIs, a React frontend, and Docker/Kubernetes deployment.

```
[ ESP32 Sensor Node ]
        │  MQTT
        ▼
[ Data Processing Service ]
        │
[ Auth Service (OAuth 2.1 / JWT) ] ◄──► [ User Management Service ]
        │
[ React Frontend ]          [ PostgreSQL / InfluxDB ]
        │
[ Docker / Kubernetes / GitHub Actions ]
```

---

## 🛠 Tech Stack

**Backend & Embedded**
`Java` `Spring Boot` `C++` `Python` `COBOL` `PlatformIO`

**IoT & Protocols**
`ESP32` `MQTT` `OAuth 2.1` `JWT` `REST`

**DevOps & Infrastructure**
`Docker` `Kubernetes` `Ansible` `GitHub Actions` `Azure`

**Databases**
`PostgreSQL` `InfluxDB` `MySQL` `DB2`

---

## 📌 Featured Projects

### 🚀 [iotApp-deployment](https://github.com/doemefu/iotApp-deployment) — Full Platform Deployment
The operational backbone of the IoT platform. Ansible playbooks bootstrap a **Raspberry Pi K3s cluster** from scratch, installing Traefik, cert-manager, and monitoring tooling. Kubernetes manifests cover all 5 microservices plus infrastructure (PostgreSQL, InfluxDB, Mosquitto). Includes a pytest validation suite for manifests and GitHub Actions CI.

`Kubernetes` `K3s` `Ansible` `Raspberry Pi` `Traefik` `GitHub Actions` `Python`

---

### 🌱 [Terra1](https://github.com/doemefu/Terra1) — ESP32 Sensor Node Firmware
C++ firmware for an ESP32 microcontroller running a smart terrarium sensor node. Reads temperature (DHT11, DS18B20), soil moisture, and light data every 30 seconds and publishes over MQTT. Architecture uses classic design patterns (Singleton, Factory, Observer, Command, State) and includes full UML documentation.

`C++` `ESP32` `MQTT` `PlatformIO` `PubSub`

---

### 🔐 [auth-service](https://github.com/doemefu/auth-service) — OAuth 2.1 Authorization Server
Production-grade authorization service built on Spring Authorization Server. Handles both interactive user flows (Authorization Code) and machine-to-machine auth (Client Credentials) — so IoT devices can authenticate directly without a user session. Stores registered clients and tokens in PostgreSQL via JDBC.

`Java 21` `Spring Boot` `OAuth 2.1` `JWT` `PostgreSQL`

---

### ⚙️ Platform Microservices
The remaining backend services rounding out the platform:
- **[user-management-service](https://github.com/doemefu/user-management-service)** — REST API for user profiles, roles (USER/ADMIN), and password management; acts as the user data source for the auth service
- **[frontIotApp](https://github.com/doemefu/frontIotApp)** — React frontend for device monitoring and user interaction
- **[iotApp-automation](https://github.com/doemefu/iotApp-automation)** — CI/CD scripts and service orchestration configs

---

## 💼 Background

Before studying, I worked as an **Application Developer at UBS** (Core Cash Accounting) — modernizing COBOL batch systems on IBM mainframes and automating cloud infrastructure with Ansible. More recently, I interned at **KPMG** in the Assurance Technology Group, conducting IT audits of ERP systems and access/change management controls.

I also spent a year as an engineer at **AMZ Racing** (ETH Zurich Formula Student team), integrating sensors into the pedal box of a race car — which is where the hardware interest started.

---

## 📊 Stats

<img src="./github-stats.svg" height="180" />
<img src="./github-top-langs.svg" height="180" />

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dominic_Furchert-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/dominic-furchert)

📍 Zurich, Switzerland
