# Awesome-Home-Automation-IOT
# Awesome-Home-Automation-IOT

# Top Home Automation & IoT Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Smart Home Control, Local Automation & IoT Interoperability*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Home Automation & IoT**. These tools connect, automate, and manage smart home devices, sensors, and appliances using local protocols (Zigbee, Z-Wave, MQTT, Matter) and cloud integrations, enabling users to build privacy-focused, vendor-agnostic smart home systems.

**Examples** include openHAB, Home Assistant Cloud, SmartThings, Apple HomeKit, Google Home, Amazon Alexa, Hubitat Elevation, Control4, Tuya Smart, and Domoticz Cloud (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local control, and open IoT data processing — ideal for smart home enthusiasts, developers, and privacy-conscious users building transparent, cloud-free automation solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Home Assistant Cloud (Nabu Casa)](https://www.nabucasa.com/)**  
  Optional paid cloud service for Home Assistant offering remote access, Alexa/Google voice integration, and secure webhooks without exposing your instance to the internet.

- **[SmartThings (Samsung)](https://www.smartthings.com/)**  
  Cloud-centric smart home hub and app ecosystem with broad device compatibility and Matter support, though local control is limited compared to open-source alternatives .

- **[Apple HomeKit](https://www.apple.com/home/)**  
  Apple's privacy-focused smart home framework with local processing, Secure Video, and deep integration across iPhone, iPad, Mac, and Apple TV.

- **[Google Home](https://home.google.com/)**  
  Google's smart home platform with Gemini AI integration, Nest device ecosystem, and Matter support for cross-platform device control.

- **[Amazon Alexa](https://developer.amazon.com/en-US/alexa)**  
  Voice-first smart home ecosystem with massive device compatibility, Alexa Routines, and Matter controller support across Echo devices.

- **[Hubitat Elevation](https://hubitat.com/)**  
  Local-first smart home hub with cloud optional, supporting Zigbee, Z-Wave, and Matter with rule-based automation engine.

- **[Control4](https://www.control4.com/)**  
  Professional custom-installation home automation platform for whole-home audio, video, lighting, and security integration.

- **[Tuya Smart](https://www.tuya.com/)**  
  Global IoT platform powering millions of white-label smart devices, with cloud APIs and app ecosystem for device manufacturers.

- **[Domoticz Cloud](https://www.domoticz.com/)**  
  Optional cloud connectivity for Domoticz users, though the core platform is designed for local self-hosting.

## Open-Source GitHub Projects

- **[Home Assistant](https://github.com/home-assistant/core)**  
  The leading open-source home automation platform with 1,600+ official integrations, local control, visual automation editor, and massive community. Ranked 1st in academic comparison for features and UX .

- **[openHAB](https://github.com/openhab/openhab-core)**  
  Vendor-neutral, model-based home automation platform with Things/Channels/Items architecture, 400+ bindings, and choice of rule engines. Ranked 2nd in academic comparison .

- **[ioBroker](https://github.com/ioBroker/ioBroker)**  
  JavaScript-based IoT integration platform with adapter concept, Redis-backed state database, and focus on building automation, smart metering, and visualization. "Automate your life!" .

- **[Domoticz](https://github.com/domoticz/domoticz)**  
  Lightweight C++ home automation system with exceptional resource efficiency (runs on 64MB RAM), excellent legacy protocol support (433MHz RF, 1-Wire), and Blockly/Lua/dzVents automation .

- **[ESPHome](https://github.com/esphome/esphome)**  
  YAML-based firmware framework for ESP8266/ESP32 devices, enabling custom smart home sensors and actuators with native Home Assistant integration .

- **[Tasmota](https://github.com/arendst/Tasmota)**  
  Alternative firmware for ESP-based devices (Sonoff, Tuya, etc.) providing local MQTT control without cloud dependency, with 11,000+ GitHub stars .

- **[Zigbee2MQTT](https://github.com/Koenkk/zigbee2mqtt)**  
  Zigbee-to-MQTT bridge eliminating proprietary hubs, supporting 3,000+ devices and enabling local control via MQTT .

- **[Z-Wave JS](https://github.com/zwave-js/node-zwave-js)**  
  Modern Z-Wave driver for Node.js, powering Home Assistant's Z-Wave integration and enabling local mesh network control .

- **[Node-RED](https://github.com/node-red/node-red)**  
  Flow-based visual programming tool for wiring together IoT devices, APIs, and services — widely used for custom home automation logic .

- **[Eclipse Mosquitto](https://github.com/eclipse/mosquitto)**  
  Lightweight MQTT broker for IoT messaging, forming the backbone of many local smart home architectures .

- **[OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway)**  
  Multi-protocol gateway bridging BLE, RF, IR, and other signals to MQTT for unified smart home integration .

- **[Scrypted](https://github.com/koush/scrypted)**  
  High-performance home video integration platform bringing cameras and doorbells into HomeKit, Google Home, and Alexa with local processing .

- **[evcc](https://github.com/evcc-io/evcc)**  
  Open-source EV charging controller with solar surplus optimization and smart home integration .

- **[WLED](https://github.com/Aircoookie/WLED)**  
  ESP-based LED strip controller with MQTT, E1.31, and Home Assistant integration for addressable lighting .

### Additional Strong Open-Source Options

- **[Gladys Assistant](https://github.com/GladysAssistant/Gladys)** — Privacy-focused home automation platform with simple setup.
- **[Jeedom](https://github.com/jeedom/core)** — French open-source home automation with plugin ecosystem.
- **[AppDaemon](https://github.com/AppDaemon/appdaemon)** — Python automation sandbox for Home Assistant.
- **[deCONZ REST Plugin](https://github.com/dresden-elektronik/deconz-rest-plugin)** — Zigbee gateway integration for ConBee/RaspBee sticks.
- **[OctoPrint](https://github.com/OctoPrint/OctoPrint)** — Snappy web interface for 3D printers, often integrated into smart home dashboards.
- **[InfluxDB](https://github.com/influxdata/influxdb)** + **[Grafana](https://github.com/grafana/grafana)** — Time-series database and visualization for long-term sensor data analysis.

**Frameworks for building custom systems**: Combine **Home Assistant**, **Zigbee2MQTT**, **ESPHome**, **Node-RED**, and **InfluxDB + Grafana** with **Ollama** for intelligent local smart home platforms. For ultra-lightweight deployments, **Domoticz** with **Mosquitto** and **Tasmota** devices delivers excellent performance on minimal hardware .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Home automation tools must comply with local electrical codes, radio regulations, and privacy laws (GDPR, CCPA).
- Self-hosted open-source solutions require proper network security (HTTPS, VPN, VLANs) and should not be exposed directly to the internet .
- Always verify device compatibility with your chosen platform before purchase, as protocol support varies by exact model and firmware.

---

**Made for smart home enthusiasts, IoT developers, privacy advocates, and automation engineers.**  
Let's make home automation more open, local, and interoperable.
