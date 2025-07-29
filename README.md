# 🌱 AgriTwinAI: Smart Urban Farming Digital Twin with AI

AgriTwinAI is an advanced smart farming system that brings together AI, IoT, and digital twin simulations to provide an immersive, data-driven, and scalable platform for urban farming. It includes real-time monitoring, AI-driven decision-making, plant disease detection, environmental sensors integration, and a virtual 3D simulation that reflects the real-world state of plants.

---

## 🚀 Project Highlights

- 🌿 **Digital Twin Simulation** of real plants (growth, health, moisture, sunlight)
- 🧠 **AI-powered Disease Detection** using CNN models
- 📡 **Sensor Integration or Simulated APIs** for real-time data
- 📈 **Smart Dashboard** with analytics (growth trends, watering logs, sunlight exposure, etc.)
- 🌍 **Interactive 3D Visualization** of the plant (basic to advanced levels)
- 🎥 **Image & Video AI Generation** for simulating changes in plant states

---

## 🔧 Tech Stack

| Layer         | Tools / Frameworks Used                                                  |
| ------------- | ------------------------------------------------------------------------ |
| Frontend      | React.js, Three.js, Tailwind CSS, Chart.js                               |
| Backend       | Node.js / Express.js (or Python Flask FastAPI alternative)               |
| AI/ML         | Python, TensorFlow/Keras or PyTorch (for CNN Plant Disease Detection)    |
| Data API      | Simulated Sensor API or Physical Device Integration (ESP32, etc.)        |
| 3D Simulation | Three.js / Babylon.js (Mid-Level), Unity WebGL (Advanced)                |
| AI Media Gen  | Gemini Vision AI (Free), Stability AI, DALL·E for images, Pika for video |

---

## 🔄 User Flow (End User)

1. **Log in / Register**
2. **Select Plant or Farm Unit**
3. **View Real-time Stats** (Moisture, Sunlight, Growth Stage)
4. **View 3D Simulation** (Plant Growth, Stress, Disease)
5. **Trigger AI Prediction** (Disease, Care Tips)
6. **Watch AI-Generated Image/Video Simulation** (Plant future/growth prediction)
7. **View Graphical Trends** (Historical growth, water, sunlight logs)

---

## 🛠 Developer Flow (Creator Side)

1. **Set up Frontend + Backend Scaffold**
2. **Train or Integrate Plant Disease CNN Model**
3. **Create REST API for sensor data (mock or hardware)**
4. **Add Three.js Simulation Components**
5. **AI Integration (Gemini, Stability AI) for image/video response**
6. **Create Real-Time Dashboard (React + Chart.js)**
7. **Link Twin Visualization to API or DB State**

---

## 💻 Repository Structure

```bash
AgriTwinAI/
├── frontend/                 # React + Three.js UI
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── assets/
├── backend/                  # Express or Flask
│   ├── routes/
│   ├── controllers/
│   └── data/
├── ml_model/                # CNN model for disease detection
│   └── training_data/
├── simulator/               # 3D rendering logic
│   └── twin_visual/
├── mock_api/                # Simulated sensor data
│   └── data_feeder.py
├── .gitignore
├── requirements.txt / package.json
└── README.md
```

---

## 🤖 Digital Twin Simulation Levels

| **Level** | **Features**                                                                                                  |
| --------- | ------------------------------------------------------------------------------------------------------------- |
| Basic MVP | Image Swapping + Text Descriptions, Chart.js graphs                                                           |
| Mid-Level | 3D with Three.js, Animation States per Condition, Blender exports                                             |
| Advanced  | Unity WebGL, Procedural AI image generation, Environmental Sim Engine, Video prediction, Physics-based Growth |

---

## 🌟 Physics-Based & Advanced Simulations

For realistic growth and environmental effects:

- Use physics engines like **Cannon.js** (for Three.js), or Unity's built-in physics
- Simulate water absorption, gravity effect on leaves, disease spread (as visual particle systems)

---

## 🔗 Free AI Tools for Image & Video

| Tool             | Use Case                          | Free?              |
| ---------------- | --------------------------------- | ------------------ |
| Gemini by Google | Plant health insights & image gen | ✅                  |
| Pika Labs        | AI-generated plant videos         | ✅                  |
| DALL·E           | Disease stage visualization       | ⚠️ Limited credits |
| Stability AI     | Open source image generation      | ✅                  |

---

## 🌿 Why This Project?

Urban farming is key to a sustainable future. AgriTwinAI brings:

- 👨‍🌾 **Empowerment to urban growers** through data and simulation
- 🧪 **Test scenarios without real-world risks** (e.g., overwatering, plant stress)
- 🛰️ **Bridge between real sensors & digital visualization**
- 🎓 **Educates students & hobbyists** about precision agriculture

---

## 🛠 Future Work

- Voice assistant for farmers
- AI chat-based suggestions
- Multi-plant digital field twins
- Cloud-based ML model hosting (e.g., HuggingFace or Google Colab)

---

## 🧪 License & Contribution

Open-source under MIT. PRs and forks are welcome!

> Made with ❤️ for the future of farming 🌱

