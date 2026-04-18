# 🌐 AetherSense – Intelligent Environmental Monitoring System


## 📌 Project Overview
AetherSense is an IoT-based environmental monitoring system designed to improve energy efficiency and indoor comfort.

Traditional HVAC systems are **occupancy-blind**, leading to energy wastage.  
This project solves that using:
- Multi-sensor data fusion  
- Real-time monitoring  
- Machine learning  

---

## 🧠 Key Features
- 🌡️ Temperature & humidity monitoring  
- 🔊 Sound-based occupancy detection  
- 💡 Light intensity tracking  
- 📊 Real-time dashboard visualization  
- 🚨 Alert system (Normal / Warning / Critical)  
- 🤖 Machine learning classification (Safe / Unsafe)  
- ☁️ Cloud-based data storage  

---

## 🏗️ System Architecture

## Schematics
![Schematic](https://raw.githubusercontent.com/tyrobee/AetherSense/main/Photos/S1.png)
## PCB
![PCB](https://raw.githubusercontent.com/tyrobee/AetherSense/main/Photos/P1.png)


### 🔹 Architecture Layers

| Layer | Description |
|------|------------|
| Sensing Layer | Collects environmental data using sensors |
| Processing Layer | RP2040 processes data |
| Cloud Layer | Stores data & runs ML model |
| Application Layer | Dashboard visualization |

---

## 🔧 Hardware Components

- RP2040 Microcontroller  
- DHT11 Temperature & Humidity Sensor  
- LM393 Sound Sensor  
- LDR Light Sensor  
- Breadboard & Connections  

---

## 💻 Software Architecture

### 🔄 Processing Pipeline


---

## 📊 Feature Vector


---

## 🤖 Machine Learning Model

| Parameter | Value |
|----------|------|
| Model | Random Forest |
| Input | Sensor Feature Vector |
| Output | Room Condition |
| Accuracy | 99.85% |

---

## 📈 Experimental Results

| Metric | Value |
|-------|------|
| Training Samples | 8103 |
| Test Samples | 2026 |
| Accuracy | 99.85% |
| OOB Accuracy | 99.75% |

---

## 🔄 System Workflow

1. Initialize system  
2. Read sensor data  
3. Process & classify values  
4. Create feature vector  
5. Perform ML inference  
6. Update dashboard  
7. Generate alerts  
8. Store data  

---

## 🚨 Alert Levels

| Level | Meaning |
|------|--------|
| 🟢 Normal | All values safe |
| 🟡 Warning | Moderate deviation |
| 🔴 Critical | Unsafe condition |

---

## 📊 Dashboard Features
- Live sensor values  
- Graphs & trends  
- System status  
- Prediction with confidence  
- Alert panel  

---

## ⚠️ Limitations
- Slow DHT11 response (5s delay)  
- Sound sensor noise sensitivity  
- Light sensor affected by weather  
- Dataset imbalance  
- Requires continuous connectivity  

---

## 🚀 Future Scope
- Faster sensors  
- Large-scale deployment  
- Better occupancy detection  
- Wireless communication  
- Adaptive ML models  

---

## 🎯 Conclusion
AetherSense provides a **smart, scalable, and cost-effective solution** for intelligent environmental monitoring using IoT and Machine Learning.

---

## 📚 References
- RP2040 Datasheet  
- DHT11 Sensor Manual  
- LM393 Datasheet  
- Kaggle Dataset  
- Random Forest Algorithm  

---

## 📄 License
This project is for academic purposes.


## 👥 Team Members
| Name | Roll Number |
|------|------------|
| Aditi Akansha | 25BCE0544 |
| Vaibhav Singh | 25BCE2492 |
| Gowshik R S | 25BCE0958 |
| Shashank Pulipati | 25BEC0573 |
| H Sharman Singh | 25BEC0076 |

---

