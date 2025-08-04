# 🩺 RecovR – Your Post-Surgery Ally

> "Doctor-Directed Recovery, Reimagined for Real Life."

![SwiftUI](https://img.shields.io/badge/SwiftUI-orange?style=for-the-badge&logo=swift&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini%20AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)

## 🌟 Overview
RecovR is a post-surgery recovery platform built for **real-time health tracking and communication** between patients and doctors. It offers:
- 📱 A mobile iOS app for patients to monitor vitals and medication schedules
- 💻 A web interface for doctors to track recovery remotely
- 🤖 Integration with **Gemini AI** for journaling, insights, and data visualization

## 🧠 Inspiration
We noticed that many post-surgery patients feel overwhelmed managing meds, vitals, and updates — especially while healing. RecovR was designed to simplify recovery, empower doctors, and reduce stress for patients.

## 🧰 Tech Stack
| Frontend (iOS)      | Backend / API        | AI/ML       | Database & Infra |
|---------------------|----------------------|-------------|------------------|
| SwiftUI             | Gemini API           | Gemini AI   | Firebase Realtime DB |
| HealthKit, WatchOS  |                      |             | Firebase Hosting     |

## 🔑 Key Features
- ❤️ **Health Monitoring**: Pulls real-time heart rate and vitals from iWatch using HealthKit
- 💊 **Medication Tracker**: Doctors can assign meds; patients receive reminders
- 📝 **AI Journal**: Gemini AI summarizes patient progress via natural language prompts
- 🧠 **Doctor Dashboard**: Web-based view of all assigned patients and their recovery status
- 🔔 **Push Notifications**: Timely alerts for medications, check-ins, and more

## 🚀 How to Run (iOS App)
> Requires macOS + Xcode + iOS device/simulator

```bash
# 1. Clone the repository
git clone https://github.com/iamVL/RecovR.git
cd RecovR

# 2. Open the Xcode project
open RecovR/RecoverRight.xcodeproj

# 3. Set up Firebase (using your config)
# Follow Firebase iOS setup to insert your GoogleService-Info.plist

# 4. Run on Simulator or Connected Device

```

## 🌐 Try It Live (Web View for Doctors)
🔗 [Live Demo](https://lahacks2024-18b32.web.app) (hosted via Firebase)

---

## 👨‍⚕️ Sample Screens

<p align="center">
  <img src="R1.png width="250""/>
  <img src="R2.png width="250""/>
  <img src="R3.png width="250""/>
</p>

---

## 🧪 Lessons Learned
- Integrated complex APIs like **Gemini AI** and **HealthKit** for the first time  
- Built seamless iOS → Firebase → Web communication in **under 36 hours**  
- Designed with **accessibility** and a **UX-first mindset** from day one  

---

## 🛠 Challenges
- Real-time data syncing across **Gemini AI**, **Firebase**, and **iOS**
- Managing push notifications and user tokens
- Coordinating frontend/backend efforts within limited hackathon time

---

## 🎓 Built With
- `SwiftUI`
- `Firebase`
- `Gemini API`
- `HealthKit`
- `JavaScript`, `HTML`, `CSS`
- `WatchOS`

---

## 🏁 Submission
This project was built and submitted at **[LA Hacks 2024](https://lahacks.com)** — *Finalist Submission* 🏆

---

## 👥 Team

| Name                    | Role                        |
|-------------------------|-----------------------------|
| [Vaishnavi Lokhande](https://github.com/iamVL) | iOS Lead, AI Integration       |
| Karthik Yadav Viyyapu   | Web Lead, Firebase Auth     |
| Adolfo Calderon         | iOS Developer, UI Designer  |
| Kafai Lei               | Documentation & Testing     |

---

## 📄 License
[MIT License](LICENSE)

---

> 🩺 Built to make recovery smoother, safer, and smarter — one heartbeat at a time.

