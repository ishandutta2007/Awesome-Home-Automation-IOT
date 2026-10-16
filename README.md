<p align="center">
  <img src="assets/banner.svg" alt="Awesome Home Automation and IoT Banner" width="100%">
</p>

# 🏡 Awesome Home Automation & IoT Ecosystem 🌐

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Home-Automation-IOT/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Home-Automation-IOT?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Home-Automation-IOT/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Home-Automation-IOT?style=social" alt="GitHub forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Home-Automation-IOT/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

> 🚀 **Curated directory of premier SaaS platforms, self-hosted open-source software, custom micro-controller firmware, and local communication protocols powering modern smart homes and Internet of Things (IoT) ecosystems.**

---

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS & Hosted Smart Home Platforms](#️-saas--hosted-smart-home-platforms)
- [🔓 Open-Source GitHub Projects & Stacks](#-open-source-github-projects--stacks)
  - [🏆 Top Open-Source Projects (by Stars)](#-top-open-source-projects-by-stars)
  - [🧩 Recommended Architecture Stacks](#-recommended-architecture-stacks)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support](#-support)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Smart Home & IoT market is projected to expand from **$120+ billion in 2024 to over $330 billion by 2030**, clocking a compound annual growth rate (CAGR) of approximately **18.5%** driven by ubiquitous edge computing, energy efficiency demands, and AI-assisted automation. 

The industry exhibits a **moderately fragmented ecosystem transitioning toward standards-based consolidation**: Big Tech hyperscalers (Apple, Google, Amazon, Samsung) dominate consumer voice interfaces and cloud backbones, while specialized IoT platforms, custom installer ecosystems (Control4, Crestron), and a robust **local-first open-source community** (led by Home Assistant, ESPHome, and Zigbee2MQTT via Matter/Thread) maintain significant influence and user retention due to heightened consumer privacy demands and vendor lock-in avoidance.

---

## ☁️ SaaS & Hosted Smart Home Platforms

Below is a comparison of major commercial and hosted smart home platforms, sorted in descending order by parent company enterprise valuation / annual market size.

| Platform / Vendor | Company Scale (Valuation / Revenue) | Starting Paid Tier Pricing | Free Tier / Trial Limit | Key Features & Architecture |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple HomeKit](https://www.apple.com/home/)** | **~$3.4 Trillion** (Market Cap) | **$0.99/mo** (iCloud+ 50GB plan for 1 HomeKit Secure Video camera stream) | **Free Forever** for standard device pairing, scenes, and local automations (requires Apple Hub device; no video recording history) | Privacy-centric smart home framework, end-to-end encrypted video, Matter controller, local execution across iOS/macOS. |
| **[Google Home](https://home.google.com/)** | **~$2.1 Trillion** (Alphabet Market Cap) | **$8.00/mo** or $80/yr (Nest Aware basic plan for 30-day event video history) | **Free Forever** for core device pairing, routines, voice assistant controls, and live camera streaming (without event clip history) | Gemini AI integration, Google Nest ecosystem, multi-protocol Matter/Thread controller, cross-platform Android/iOS UI. |
| **[Amazon Alexa](https://developer.amazon.com/en-US/alexa)** | **~$1.9 Trillion** (Market Cap) | **$4.99/mo** or $49.99/yr (Ring Protect Basic / Blink Plus plan for single camera cloud history) | **Free Forever** for voice automation, routine engine, Matter hub pairing, and skill invocation across Echo hardware | Voice-first smart home ecosystem, broad third-party appliance compatibility, Alexa Routines, and Matter controller. |
| **[SmartThings](https://www.smartthings.com/)** | **~$380 Billion** (Samsung Market Cap) | **Hardware-bound** (Requires SmartThings Hub / Samsung Smart TV / Appliance from $35-$120) | **Free Forever** cloud and local hub access with unlimited connected devices, rules, and mobile app usage | Multi-protocol hub (Zigbee, Z-Wave, Thread, Matter), cloud rules engine with expanding local Edge Driver execution. |
| **[Tuya Smart](https://www.tuya.com/)** | **~$1.1 Billion** (Market Cap / NYSE: TUYA) | **$25.00/mo** (Tuya IoT Core API Basic Cloud Developer subscription tier) | **Free Trial for 1 month** with 50 trial device licenses and 1,000,000 monthly API call quota | World's largest IoT cloud PaaS, powering tens of thousands of white-label hardware OEMs with unified Tuya Smart Life APIs. |
| **[Control4](https://www.control4.com/)** | **~$800 Million** (Snap One / Resideo Technologies Segment) | **$120.00/yr** (Control4 4Sight remote access, voice integration, and cloud backup subscription) | **90-Day Free Trial** of 4Sight cloud features included with professional hardware installation | Enterprise luxury custom-install home automation, multi-room audio/video distribution, lighting panels, and surveillance. |
| **[Hubitat Elevation](https://hubitat.com/)** | **~$15 Million** (Estimated Revenue / Privately Held) | **$3.99/mo** or $39.99/yr (Hubitat Remote Admin cloud service) | **Free Forever** complete local automation execution on the Hubitat Elevation Hub hardware (no cloud subscription needed) | Local-first Zigbee, Z-Wave, LAN, and Matter hub with Rule Machine engine; operates 100% offline without cloud connectivity. |
| **[Home Assistant Cloud (Nabu Casa)](https://www.nabucasa.com/)** | **~$10 Million** (Estimated ARR / Nabu Casa Inc.) | **$6.50/mo** or $65.00/yr (Nabu Casa Subscription) | **31-Day Free Trial** with full features (remote access, secure Alexa & Google Assistant voice linking, webhook relays) | Direct zero-config remote access and end-to-end encrypted voice proxying for self-hosted Home Assistant instances. |
| **[Domoticz Cloud](https://www.domoticz.com/)** | **~$1 Million** (Community Supported Open-Core) | **$2.50/mo** (approx. €2.00/mo for community web proxy and push service) | **Free Forever** self-hosted local instance with full web UI and MQTT capabilities without mandatory subscriptions | Extremely lightweight community automation dashboard and cloud-relay for embedded systems and legacy IoT protocols. |

---

## 🔓 Open-Source GitHub Projects & Stacks

### 🏆 Top Open-Source Projects (by Stars)

The table below lists the premier open-source smart home engines, firmwares, gateways, and observability tools, sorted by GitHub_Stars_Count:

| Project | GitHub_Stars_Badge | Primary Purpose | Tech Stack |
| :--- | :--- | :--- | :--- |
| **[Home Assistant](https://github.com/home-assistant/core)** | [![Stars](https://img.shields.io/github/stars/home-assistant/core?style=social&color=white)](https://github.com/home-assistant/core/stargazers) | The gold standard open-source local-first home automation hub with 2,500+ integrations. | Python, Asyncio, WebSockets |
| **[Grafana](https://github.com/grafana/grafana)** | [![Stars](https://img.shields.io/github/stars/grafana/grafana?style=social&color=white)](https://github.com/grafana/grafana/stargazers) | The leading observability platform for visualizing IoT sensor telemetry, power usage, and trends. | TypeScript, Go, React |
| **[Frigate NVR](https://github.com/blakeblackshear/frigate)** | [![Stars](https://img.shields.io/github/stars/blakeblackshear/frigate?style=social&color=white)](https://github.com/blakeblackshear/frigate/stargazers) | Real-time local NVR designed for Home Assistant with Google Coral AI hardware object detection. | Python, OpenCV, MQTT |
| **[InfluxDB](https://github.com/influxdata/influxdb)** | [![Stars](https://img.shields.io/github/stars/influxdata/influxdb?style=social&color=white)](https://github.com/influxdata/influxdb/stargazers) | Scalable time-series database optimized for smart home temperature, humidity, and energy metrics. | Go, Rust |
| **[Tasmota](https://github.com/arendst/Tasmota)** | [![Stars](https://img.shields.io/github/stars/arendst/Tasmota?style=social&color=white)](https://github.com/arendst/Tasmota/stargazers) | Alternative open-source firmware for ESP8266/ESP32 devices providing full local MQTT and HTTP control. | C++, ESP-IDF, MQTT |
| **[Node-RED](https://github.com/node-red/node-red)** | [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | Low-code flow-based visual programming environment for event-driven IoT automation and API wiring. | JavaScript, Node.js |
| **[WLED](https://github.com/Aircoookie/WLED)** | [![Stars](https://img.shields.io/github/stars/Aircoookie/WLED?style=social&color=white)](https://github.com/Aircoookie/WLED/stargazers) | Fast and feature-rich ESP32/ESP8266 controller for addressable NeoPixel/WS2812B LED light installations. | C++, PlatformIO, E1.31 |
| **[Zigbee2MQTT](https://github.com/Koenkk/zigbee2mqtt)** | [![Stars](https://img.shields.io/github/stars/Koenkk/zigbee2mqtt?style=social&color=white)](https://github.com/Koenkk/zigbee2mqtt/stargazers) | Hub-free bridge connecting Zigbee devices from 400+ brands directly into any MQTT broker. | TypeScript, Node.js |
| **[go2rtc](https://github.com/AlexxIT/go2rtc)** | [![Stars](https://img.shields.io/github/stars/AlexxIT/go2rtc?style=social&color=white)](https://github.com/AlexxIT/go2rtc/stargazers) | Zero-latency RTSP/WebRTC/HLS camera streaming server engineered specifically for smart home dashboards. | Go, WebRTC |
| **[ESPHome](https://github.com/esphome/esphome)** | [![Stars](https://img.shields.io/github/stars/esphome/esphome?style=social&color=white)](https://github.com/esphome/esphome/stargazers) | Declarative YAML-based firmware framework creating plug-and-play custom smart sensors and relays. | C++, Python, ESP-IDF |
| **[Eclipse Mosquitto](https://github.com/eclipse/mosquitto)** | [![Stars](https://img.shields.io/github/stars/eclipse/mosquitto?style=social&color=white)](https://github.com/eclipse/mosquitto/stargazers) | Ultra-lightweight MQTT v5.0/v3.1.1 message broker serving as the communications backplane of IoT networks. | C |
| **[OctoPrint](https://github.com/OctoPrint/OctoPrint)** | [![Stars](https://img.shields.io/github/stars/OctoPrint/OctoPrint?style=social&color=white)](https://github.com/OctoPrint/OctoPrint/stargazers) | The standard web interface and print monitoring platform for 3D printers with smart home plugins. | Python, Flask, Knockout.js |
| **[evcc](https://github.com/evcc-io/evcc)** | [![Stars](https://img.shields.io/github/stars/evcc-io/evcc?style=social&color=white)](https://github.com/evcc-io/evcc/stargazers) | Smart Electric Vehicle charging controller optimizing clean solar surplus energy and dynamic tariffs. | Go, Vue.js |
| **[Scrypted](https://github.com/koush/scrypted)** | [![Stars](https://img.shields.io/github/stars/koush/scrypted?style=social&color=white)](https://github.com/koush/scrypted/stargazers) | High-performance home video integration engine bringing local camera streams into HomeKit Secure Video. | TypeScript, WebAssembly |
| **[OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway)** | [![Stars](https://img.shields.io/github/stars/1technophile/OpenMQTTGateway?style=social&color=white)](https://github.com/1technophile/OpenMQTTGateway/stargazers) | Universal gateway bridging BLE beacons, 433MHz/315MHz RF, IR transmitters, and LoRa directly to MQTT. | C++, PlatformIO |
| **[Domoticz](https://github.com/domoticz/domoticz)** | [![Stars](https://img.shields.io/github/stars/domoticz/domoticz?style=social&color=white)](https://github.com/domoticz/domoticz/stargazers) | Ultra-lightweight C++ home automation server designed to run efficiently even on 64MB RAM devices. | C++, HTML5, Lua |
| **[Gladys Assistant](https://github.com/GladysAssistant/Gladys)** | [![Stars](https://img.shields.io/github/stars/GladysAssistant/Gladys?style=social&color=white)](https://github.com/GladysAssistant/Gladys/stargazers) | Modern, privacy-first smart home assistant with an intuitive dashboard and built-in Zigbee management. | Node.js, Preact, Docker |
| **[Music Assistant](https://github.com/music-assistant/server)** | [![Stars](https://img.shields.io/github/stars/music-assistant/server?style=social&color=white)](https://github.com/music-assistant/server/stargazers) | Multi-room, vendor-agnostic music streamer uniting Sonos, AirPlay, Chromecast, and local audio libraries. | Python, Asyncio |
| **[deCONZ REST Plugin](https://github.com/dresden-elektronik/deconz-rest-plugin)** | [![Stars](https://img.shields.io/github/stars/dresden-elektronik/deconz-rest-plugin?style=social&color=white)](https://github.com/dresden-elektronik/deconz-rest-plugin/stargazers) | Hardware driver and REST interface for Dresden Elektronik ConBee and RaspBee Zigbee coordinators. | C++, Qt |
| **[ioBroker](https://github.com/ioBroker/ioBroker)** | [![Stars](https://img.shields.io/github/stars/ioBroker/ioBroker?style=social&color=white)](https://github.com/ioBroker/ioBroker/stargazers) | Modular, adapter-driven IoT integration platform with deep European smart meter and KNX support. | JavaScript, Redis, Node.js |
| **[openHAB](https://github.com/openhab/openhab-core)** | [![Stars](https://img.shields.io/github/stars/openhab/openhab-core?style=social&color=white)](https://github.com/openhab/openhab-core/stargazers) | Enterprise-grade, vendor-neutral smart home system with OSGi modular architecture and rule engine. | Java, OSGi |
| **[zigpy](https://github.com/zigpy/zigpy)** | [![Stars](https://img.shields.io/github/stars/zigpy/zigpy?style=social&color=white)](https://github.com/zigpy/zigpy/stargazers) | Python library implementing pure Zigbee protocol stack powering Home Assistant's ZHA integration. | Python, Asyncio |
| **[AppDaemon](https://github.com/AppDaemon/appdaemon)** | [![Stars](https://img.shields.io/github/stars/AppDaemon/appdaemon?style=social&color=white)](https://github.com/AppDaemon/appdaemon/stargazers) | Python execution environment enabling complex, multithreaded, programmatic automations for Home Assistant. | Python |
| **[Z-Wave JS](https://github.com/zwave-js/zwave-js)** | [![Stars](https://img.shields.io/github/stars/zwave-js/zwave-js?style=social&color=white)](https://github.com/zwave-js/zwave-js/stargazers) | High-performance, standards-compliant Z-Wave device driver and controller powering the global ecosystem. | TypeScript, Node.js |
| **[Jeedom](https://github.com/jeedom/core)** | [![Stars](https://img.shields.io/github/stars/jeedom/core?style=social&color=white)](https://github.com/jeedom/core/stargazers) | Modular French home automation server with extensive multi-protocol marketplace plugins. | PHP, JavaScript, MySQL |

---

### 🧩 Recommended Architecture Stacks

For builders creating resilient, private, cloud-free smart homes:

- 🏠 **The Gold Standard Local Stack**:
  - **Hub**: [Home Assistant](https://github.com/home-assistant/core) on an x86 Mini PC or Raspberry Pi 5
  - **Wireless Gateways**: [Zigbee2MQTT](https://github.com/Koenkk/zigbee2mqtt) with a Sonoff / SLZB Zigbee 3.0 coordinator + [Z-Wave JS](https://github.com/zwave-js/zwave-js)
  - **Custom Sensors / Relays**: [ESPHome](https://github.com/esphome/esphome) on ESP32 microcontrollers
  - **Communications Backbone**: [Eclipse Mosquitto](https://github.com/eclipse/mosquitto) MQTT Broker
  - **Video Streaming & AI Detection**: [Frigate NVR](https://github.com/blakeblackshear/frigate) with Google Coral accelerator + [go2rtc](https://github.com/AlexxIT/go2rtc)
  - **Observability**: [InfluxDB](https://github.com/influxdata/influxdb) + [Grafana](https://github.com/grafana/grafana) for long-term historical environmental telemetry

- ⚡ **Ultra-Low Footprint Stack**:
  - **Server**: [Domoticz](https://github.com/domoticz/domoticz) running on 64MB RAM single-board computer
  - **Firmware**: [Tasmota](https://github.com/arendst/Tasmota) on ESP8266 smart plugs
  - **Broker**: [Eclipse Mosquitto](https://github.com/eclipse/mosquitto)

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help expand this comprehensive directory:

1. 🍴 **Fork the repository** on GitHub.
2. 🌿 **Create a feature branch** (`git checkout -b feature/new-iot-platform`).
3. 📝 **Add/edit entries** in `README.md` keeping formatting clean, alphabetical, or sorted by Stars_Count/market cap.
4. 🔗 Include official homepage, GitHub repository link, clear licensing, and concise factual descriptions.
5. 🚀 **Submit a Pull Request** with a brief summary of the addition.

---

## 💖 Support

If this repository assisted you in architecting, automating, or freeing your smart home from cloud lock-in, please consider showing your support:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork and share** with your local IoT and maker communities.
- ☕ **Buy a coffee or sponsor ongoing maintenance**: [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007)

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Home-Automation-IOT&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Home-Automation-IOT&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This repository is a community-curated educational resource and does not constitute formal endorsement.
- Electrical home automation devices must strictly comply with local electrical safety regulations (NEC, CE, UL) and RF radio standards (FCC, ETSI).
- Ensure network segregation (IoT VLANs, firewall rules, VPN tunnels) when deploying self-hosted infrastructure. Avoid exposing raw management interfaces directly to the public internet.

---

<p align="center">
  <b>Built with ❤️ for smart home enthusiasts, IoT engineers, and privacy advocates.</b>
</p>
