# 👶🍼 Smart Baby Care System - Web Dashboard

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

Welcome to the frontend repository of the **Smart Baby Care System**. This project was developed as the main hardware project for the **EE2044 - Electrical Measurements and Instrumentation** module at the Department of Electrical Engineering, University of Moratuwa.

🌐 **Live Dashboard:** [Click here to view the Web App](https://senuja-dilmith.github.io/smart-baby-care-web/) *(Note: Replace with your exact GitHub Pages URL if different)*

## 📖 About This Repository
This repository hosts the User Interface (UI) and frontend logic for our IoT-enabled automated cradle system. The web app is built with HTML, CSS, and JavaScript, hosted entirely on **GitHub Pages**. It communicates seamlessly with our physical hardware setup in real-time using **Firebase**.

## ✨ Key Features of the Web App
The dashboard allows parents to monitor and control the smart cradle remotely:
* **Live Environment Monitoring:** View real-time room temperature and light levels (Lux).
* **Smart Alerts & Status:** Receive instant UI updates on:
  * Baby's presence in the crib (Powered by Hugging Face ML models via ESP32-CAM)
  * Crying detection status
  * Bed wet status (via DAQ wet sensor)
  * Cradle movement and safety (Tilt angle alerts)
* **Remote Actuator Control:**
  * Toggle the room cooling fan manually.
  * Deploy or reset the automated mosquito net instantly.
  * Set custom automated timers for the mosquito net.

## 🛠️ The Complete System Tech Stack
While this repository only contains the web frontend, the entire physical system relies on a robust hardware-software integration:
* **Frontend:** HTML, CSS, JavaScript (Hosted on GitHub Pages)
* **Backend & Cloud:** Firebase Realtime Database
* **Core Logic & Controllers:** NI DAQ Card, Arduino, LabVIEW
* **Machine Learning:** Hugging Face API
* **Custom Hardware:** 6 diverse sensors (including a custom-calibrated mechanical angle sensor) and 5 actuators (Fan, Heavy-duty Swing Servo, Net Deploy Mechanisms).

## 👥 Meet the Team
This system was engineered by undergraduate students from the University of Moratuwa:
* **Senuja Dilmith**
* **Kisal Dias**
* **Mahimi**

---
*Built with ❤️ for EE2044 | University of Moratuwa, Sri Lanka*
🌐 **Visit on linkdin** [Click here ](https://www.linkedin.com/posts/senuja-dilmith-745825349_engineering-iot-labview-ugcPost-7477016079890923520-kYB9/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFcnN-UBbr5jnr6E6rHCfVg78KUNn9FJ8jc) 
