# 🏥 Palliative Care App (تطبيق الرعاية التلطيفية)

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-teal?style=for-the-badge)

A comprehensive, cross-platform healthcare application built with **Flutter** and **Firebase**, specifically designed to support patients requiring palliative care and chronic disease management. The platform bridges the gap between patients and specialized doctors through real-time consultations, medical articles, and educational video content.

---

## ✨ Key Features

* **Role-Based Access Control (RBAC):** Dedicated interfaces, permissions, and workflows for both **Patients** and **Doctors**.
* **Chronic Disease Categories:** Specialized medical hubs for Cancer, Alzheimer's, Liver Failure, Lung Diseases, Bone Marrow Disorders, and Neurological conditions.
* **Doctor Dashboard & Content Management:** Physicians can publish, edit, and manage medical articles and educational videos directly from the app.
* **Real-Time Consultations:** Instant messaging, voice, and video call capabilities connecting patients directly with healthcare professionals.
* **Topic Subscription & Alerts:** Patients can subscribe to specific disease categories to receive tailored updates and medical guidance.
* **Secure Authentication:** Complete user authentication system with email verification and profile management powered by Firebase Auth.

---

## 📱 UI Gallery (App Screens)

### Patient Journey & Medical Categories
| Login | Registration (Role) | Patient Home | Categories | Disease Details |
| :---: | :---: | :---: | :---: | :---: |
| <img src="screenshots/login.png" width="160"/> | <img src="screenshots/register.png" width="160"/> | <img src="screenshots/patient_home.png" width="160"/> | <img src="screenshots/categories.png" width="160"/> | <img src="screenshots/disease_details.png" width="160"/> |

### Doctor Dashboard, Consultations & Profile
| Doctor Home | Create Content | Doctor Search & Messages | Live Chat | User Profile |
| :---: | :---: | :---: | :---: | :---: |
| <img src="screenshots/doctor_home.png" width="160"/> | <img src="screenshots/create_content.png" width="160"/> | <img src="screenshots/messages.png" width="160"/> | <img src="screenshots/chat.png" width="160"/> | <img src="screenshots/profile.png" width="160"/> |

> 📂 **[View All 35+ App Screens (Full UI Gallery)](./screenshots)**

---

## 🛠️ Tech Stack & Architecture

* **Framework:** Flutter (Dart)
* **Backend & Database:** Firebase (Cloud Firestore, Firebase Auth, Firebase Storage)
* **Architecture:** Clean MVC Modular Structure (`controller`, `model`, `view`, `firebase`)
* **Responsive UI:** Built with `flutter_screenutil` for pixel-perfect scaling across all screen sizes.

```text
lib/
├── controller/   # Business logic & state management
├── firebase/     # Auth, Firestore, and Storage services
├── model/        # Data models & entities
├── view/         # UI screens & custom widgets
└── main.dart     # Application entry point
```

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/dev-obadamarouf/palliative-care-app.git](https://github.com/dev-obadamarouf/palliative-care-app.git)
   ```
2. **Navigate to the project folder:**
   ```bash
   cd palliative-care-app
   ```
3. **Install dependencies:**
   ```bash
   flutter pub get
   ```
4. **Run the application:**
   ```bash
   flutter run
   ```

---

## 👨‍💻 Author

**Obada Marouf (Ibrahim Saeed Marouf)**
* GitHub: [@dev-obadamarouf](https://github.com/dev-obadamarouf)
