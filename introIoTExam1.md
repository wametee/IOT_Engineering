# Senior-Level "Introduction to IoT" Exam — introIoTExam1

Duration: 90 minutes
Total Marks: 100
Format: 5 Sections (MCQs, Short Answers, Problem-Solving, Design Case, Debug/Review)

---

## Section A — Conceptual MCQs (20 marks)
(4 marks each, choose the most correct option — some have multiple correct answers)

1. Which of the following best explains the trade-off when choosing LoRaWAN over Wi-Fi for IoT sensor networks?

A. LoRaWAN has higher throughput but shorter range.

B. LoRaWAN offers long range and low power at the cost of bandwidth.

C. Wi-Fi consumes less power than LoRaWAN.

D. LoRaWAN requires a local gateway for cloud access.

2. In an IoT system using MQTT, what is the key advantage of the publish–subscribe model?

A. Reduces latency in real-time systems.

B. Decouples producers and consumers of data.

C. Requires direct socket connections between devices.

D. Prevents the need for cloud connectivity.

3. The primary reason to perform analytics at the edge rather than the cloud is:

A. Cheaper hardware.

B. Lower latency and reduced bandwidth usage.

C. Simplified model training.

D. Easier OTA updates.

4. Which of the following sensors would be least appropriate for detecting gas leaks in a factory?

A. MQ-05

B. Ultrasonic

C. IR

D. MQ-02

5. What is the main difference between NB-IoT and LTE-M?

A. NB-IoT supports higher data rates.

B. LTE-M has lower latency and supports mobility.

C. NB-IoT supports voice calls.

D. LTE-M operates only in unlicensed bands.

---

## Section B — Short Answers (20 marks)
(4–5 lines each, 5 marks per question)

1. Explain the role of gateways in IoT architecture and list two major functions they perform.

2. Define interoperability in IoT systems and describe one approach to achieving it.

3. Why is power management crucial for IoT devices? Mention two engineering techniques used to extend battery life.

4. Contrast edge computing and fog computing with one real-world example for each.

5. Describe how over-the-air (OTA) updates contribute to system maintainability and security.

---

## Section C — Problem-Solving / Calculation (20 marks)

1. You’re designing a temperature-sensing node using LoRaWAN that samples every 15 minutes and transmits 20 bytes per sample.

- Uplink time = 2 seconds per transmission
- Current draw: 30 mA during transmit, 20 µA during sleep
- Battery = 2000 mAh

Estimate the expected battery life in months. (Show reasoning, assume 30 days/month) [12 marks]

2. You have to choose between Zigbee and BLE for a smart-home lighting network of 80 bulbs spread across a house. Compare both protocols in terms of range, power, and scalability, and justify your final choice. [8 marks]

---

## Section D — System Design Case Study (25 marks)

Design Challenge: Smart Greenhouse System

Design an IoT system for monitoring and controlling a greenhouse. Answer in ~10 concise bullet points and include the following:

- Sensors & Actuators: list at least 5 with justification.
- Connectivity: choose one (or hybrid) technology and justify based on range, cost, and power.
- Data flow: describe how data moves from sensor → cloud → user interface.
- Edge vs Cloud processing: which functions should be handled where, and why?
- Security considerations: at least 3 mechanisms to secure data and devices.

Marks: 25

---

## Section E — Debugging / Design Review (15 marks)

You’ve been asked to review the following IoT design note:

"All devices send raw sensor readings every second directly to the cloud via HTTP.
Security is optional since we operate in a closed network.
Firmware updates require physical USB access.
Power supply is a 2000 mAh battery, expected to last 1 year."

Identify four critical design flaws in this plan and propose one engineering fix for each. (15 marks)

---

## Bonus (Optional, 5 marks)
Explain how machine learning can be integrated into IoT systems for predictive maintenance. Provide one example and outline the data flow.

---

End of Exam. Good luck.
