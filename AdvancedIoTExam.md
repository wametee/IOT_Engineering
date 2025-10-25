# Final Examination — Advanced Internet of Things (IoT Systems & Applications)

**Duration:** 3 hours  **Total Marks:** 100  **Exam Type:** Written + Design + Analytical
**Instructions:** All questions are compulsory. Use real-world examples. Label diagrams clearly. Precision, logic, and applied reasoning will be rewarded.

---

## Section A: IoT Fundamentals in Real Contexts (20 marks)

**(5 marks)** Explain the differences between Cyber-Physical Systems (CPS) and IoT Systems.
Using the example of Petinder Smart Collar and Smart Greenhouse Irrigation Controller, discuss how edge intelligence transforms both products into autonomous IoT ecosystems rather than simple connected devices.

**(5 marks)** A smart hospital uses wearable health monitors to track patients’ vitals (ECG, SPO2, temperature).
- Identify and describe four sensor types used.
- Explain how data is preprocessed at the edge to reduce network congestion.

**(5 marks)** Compare Wi-Fi 6, LoRaWAN, and NB-IoT for the following use cases:
- Real-time pet location tracking in Nairobi
- Smart irrigation on a 50-acre maize farm in Nakuru
- Patient monitoring in a city hospital
Support your answer with reasoning related to bandwidth, latency, and energy efficiency.

**(5 marks)** Explain with a diagram how a multi-protocol gateway could connect the following IoT ecosystems into one cloud dashboard:
- Smart pet collars (BLE + Wi-Fi)
- Smart home systems (Zigbee + MQTT)
- Smart agriculture sensors (LoRaWAN)

---

## Section B: IoT Hardware, Data Acquisition & Embedded Systems (20 marks)

**(5 marks)** Design a sensor node for a Smart Cow Collar that tracks heart rate, location, and rumination sounds.
List all components (MCU, sensors, communication modules, power source) and explain how power optimization is achieved in remote areas.

**(5 marks)** Explain how edge AI can be deployed on Raspberry Pi or ESP32 to detect abnormal pet behavior (e.g., excessive scratching or inactivity).
Include model deployment, sensor data fusion, and latency trade-offs.

**(5 marks)** A smart home uses a mesh network to connect 300 IoT devices. Discuss how Zigbee mesh topology ensures scalability and reliability.
What are its weaknesses in high-interference urban areas? Suggest mitigation techniques.

**(5 marks)** A wearable device for elderly people monitors fall detection and heart rate using accelerometer + photoplethysmography (PPG) sensors.
Explain how data fusion improves accuracy and describe a typical firmware architecture for this system.

---

## Section C: IoT Communication & Networking Architecture (30 marks)

**(10 marks)** You are designing the PetSmart Cloud Infrastructure to support:
- 10,000 smart collars
- 500 smart homes
- 100 smart farms
Design a layered IoT architecture (Device → Edge → Cloud → Application).
Include:
- Communication protocols
- Network security layers
- API management
- Data routing & latency reduction mechanisms

**(10 marks)** Compare MQTT, AMQP, and HTTP/2 for transmitting time-critical IoT data.
For each of the following cases, justify your protocol choice:
- Smart pet activity monitoring (small data, frequent transmission)
- Real estate energy dashboards (medium data, moderate frequency)
- Remote surgery monitoring system (high data, ultra-low latency)

**(10 marks)** A smart city project in Nairobi integrates traffic sensors, air-quality monitors, and animal tracking collars into a unified cloud.
Describe how you would ensure interoperability, QoS prioritization, and scalability using edge computing, message brokers, and containerized microservices.

---

## Section D: IoT Data, Security, and AI Integration (30 marks)

**(10 marks)** A smart agriculture firm is losing sensor data due to network outages.
Propose a fault-tolerant data pipeline that uses:
- MQTT QoS levels
- Local caching on edge gateways
- Time-series database (e.g., InfluxDB)
Explain how this ensures data integrity and synchronization with the cloud.

**(10 marks)** Design a cybersecurity framework for an IoT system used across pet health, human health, and real estate.
Include:
- Device authentication
- Encryption protocols
- Firmware update policy
- Intrusion detection
- Privacy management under data regulations (GDPR, HIPAA)

**(10 marks)** Propose a machine learning model pipeline for predicting pet health anomalies using multi-modal IoT data (temperature, heart rate, motion).
Include data acquisition, preprocessing, model training, deployment, and feedback loops.
How would you address data bias between different pet breeds?

---

## Section E: Capstone Design Question (Bonus – 10 marks)

**(10 marks)** You are leading an IoT startup that builds an integrated smart ecosystem:
- Pet collars → detect stress and location
- Smart homes → adjust ambient temperature for pets and humans
- Smart agriculture → adjusts feeding schedules for livestock
Design a unified IoT ecosystem architecture diagram connecting these verticals.
Include:
- Cloud services (AWS IoT Core, Azure IoT Hub, or GCP IoT Core)
- Edge nodes
- AI decision layer
- Security and analytics pipeline

---

_End of Exam. All answers should use real-world examples and clearly labeled diagrams where appropriate._
