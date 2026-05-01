# 🌦️ Weather Emergency Response GenAI Agent

## 📌 Overview  
This project is a **semi-complex Generative AI (GenAI) agent** designed to simulate a real-world **weather emergency response system**. It combines **real-time weather data**, **decision-making logic**, and **LLM-generated responses** to analyse potential risks and trigger appropriate actions such as emergency plans and email alerts.  

The goal of this project was to move beyond simple model building and develop a **complete end-to-end AI system** that reflects how AI is used in real-world applications.

---

## 🚀 Key Features  

- 🌍 **Real-Time Weather Data Retrieval**  
  Uses the OpenWeather API to collect live weather data (temperature, wind speed, humidity, etc.)

- 🧠 **Disaster Analysis & Severity Assessment**  
  Applies rule-based logic to determine potential disaster types and severity levels  

- 🤖 **GenAI Response Generation**  
  Uses an LLM (**Gemini 1.5 Flash**) to generate emergency response plans based on context  

- 👤 **Human-in-the-Loop Decision Making**  
  Requires human approval for low/medium severity cases while allowing automation for high severity  

- 📧 **Automated Email Alerts**  
  Sends structured emergency alerts via email based on system output  

- 🧾 **System Logging & Traceability**  
  Tracks actions and decisions for transparency and reliability  

---

## ⚙️ How It Works  

The system follows a structured pipeline:

1. **Get Weather Data**  
   Retrieve real-time weather information using the OpenWeather API  

2. **Analyse Disaster**  
   Identify potential risks based on weather conditions  

3. **Assess Severity**  
   Classify the situation into severity levels (low, medium, high)  

4. **Generate Response**  
   Use GenAI to create an emergency response plan  

5. **Decision Layer**  
   - Low/Medium → requires human verification  
   - High → automatic response  

6. **Send Alert**  
   Trigger an email notification with all relevant information  

---

## 🧠 Skills & Concepts Demonstrated  

- API Integration (OpenWeather)  
- Secure handling of API keys (environment variables / secrets)  
- Real-time data retrieval and processing  
- Generative AI integration into systems  
- Decision-making logic and rule-based AI  
- Human-in-the-loop system design  
- Email automation using SMTP  
- End-to-end AI system design  

---

## 🛠️ Tech Stack  

- **Python**  
- **Google Colab**  
- **OpenWeather API**  
- **Google Gemini (LLM)**  
- **SMTP (Email integration)**  

## 📖 Inspiration / Source  

This project was inspired by and partially based on:  

👉 https://github.com/NirDiamant/GenAI_Agents/tree/main  

The project was extended by adding:
- Real-time API integration  
- Email alert system  
- Severity-based decision logic  
- Full system workflow  

---

## 🎯 Purpose  

This project was created to:
- Develop **practical, industry-relevant AI skills**  
- Understand how AI systems work beyond just models  
- Explore how **GenAI can be integrated into real-world applications**  

---

## 🔮 Future Improvements  

- Deploy as a web application (**Streamlit / FastAPI**)  
- Add more advanced disaster detection logic  
- Integrate additional data sources (e.g., alerts, sensors)  
- Improve UI and user interaction  
- Add database logging and dashboards  
