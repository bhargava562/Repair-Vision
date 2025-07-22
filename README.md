# 🔧 Repair Vision - AI-Powered Damage Detection & Repair Assistant

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tech](https://img.shields.io/badge/Built%20With-Flutter%20%26%20SpringBoot-orange)
![Firebase](https://img.shields.io/badge/Backend-Firebase-brightgreen)
![Status](https://img.shields.io/badge/Status-Prototype%20In%20Development-yellow)

> 📱 Scan → 🧠 Detect → 💵 Estimate → 🛠️ Repair → 🎥 Watch → ✅ Done!

---

## 🧠 Project Overview

**Repair Vision** is an AI-powered mobile application that helps users:

- 📸 Scan damaged items using phone camera
- 🧠 Automatically detect damage using **Gemini Vision API**
- 💰 Get instant repair cost estimation
- 📄 View AI-generated **step-by-step textual guide**
- 🎥 Watch relevant **YouTube repair videos**, or
- 🤖 Generate custom repair videos using AI tools like **RunwayML / Sora**
- ☁️ All securely integrated via **Firebase** and served via **Spring Boot API**

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 📷 **Image-Based Damage Detection** | Use camera to scan object and detect the damage automatically |
| 🤖 **Gemini Vision + LLM Prompting** | Uses multimodal AI to generate detailed repair instructions |
| 💵 **Cost Estimation Engine** | Calculates approximate repair cost using pricing APIs |
| 🎥 **YouTube + AI Repair Videos** | Fetches videos from YouTube or creates AI-generated ones if none available |
| 🔁 **Fallback + Self-Heal Mode** | When human content is unavailable, AI fills the gap with repair plans |
| ☁️ **Cloud-Backed** | All data synced to Firebase Firestore + Storage |
| 💬 **Cross-Platform UI** | Built using Flutter for seamless Android & iOS experience |

---

## 🛠️ Tech Stack

| Layer | Tech Used |
|-------|-----------|
| 🖼️ **Frontend** | Flutter (Dart) |
| 🔙 **Backend** | Spring Boot (Java) |
| ☁️ **Database** | Firebase Firestore |
| 🧠 **AI Models** | Gemini Vision API + Gemini Pro |
| 🎥 **Video** | YouTube API + AI Tools (RunwayML, Sora) |
| ☁️ **Storage** | Firebase Storage |

---

## 📱 Screenshots (Coming Soon)

> UI under development — mockups will be added here...

---

## 🧪 Current Development Status

- ✅ Flutter UI: Basic screens (Camera, Result, Video)
- ✅ Firebase integration for Firestore & Storage
- ✅ Gemini Vision integration tested via Spring Boot
- 🛠️ Video fetch + AI fallback module in progress
- 🚧 Testing + polishing pipeline in active phase

---

## 👥 Target Users

- 🧑‍🔧 **DIY Enthusiasts** (self-repair mobile, laptop, electronics)
- 🏢 **Insurance & Logistics** (automated claim/damage reporting)
- 🛠️ **Repair Shops & Field Technicians**
- 📦 **Rental & e-commerce platforms** (return condition checks)

---

## 📈 Future Scope

- 🌐 Multilingual AI repair instructions
- 🤝 Integration with 3rd-party eCommerce (for parts)
- 🧩 Plugin SDK for logistics/insurance dashboards
- 🔒 Offline mode with lightweight ML models

---

## 📎 How to Run Locally

### 🎯 Flutter Frontend

```bash
cd frontend
flutter pub get
flutter run
```

### 🚀 Spring Boot Backend

```bash
cd backend
./mvnw spring-boot:run
```

### 🔥 Firebase Setup

1. Add your Firebase config in `/lib/firebase_options.dart`
2. Enable Firestore and Storage
3. Configure authentication if required

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 💡 Contributing

We welcome contributions! Please open issues or pull requests if you'd like to help improve Repair Vision.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📬 Contact

👨‍💻 **Developer:** Bhargava A.  
✉️ **Email:** your-email@example.com  
🌐 **Portfolio:** [Coming Soon]

---

## 🙏 Acknowledgments

- Google Gemini AI for powerful vision capabilities
- Firebase for seamless backend integration
- Flutter team for cross-platform framework
- YouTube API for video content access
- Open source community for inspiration

---
