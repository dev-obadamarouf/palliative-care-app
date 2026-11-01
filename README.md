# 🏥 Palliative Care App (تطبيق الرعاية التلطيفية)

A comprehensive, cross-platform healthcare application built with **Flutter** and **Firebase**, specifically designed to support patients requiring palliative care and chronic disease management. The platform bridges the gap between patients and specialized doctors through real-time consultations, medical articles, and educational video content.

---

## ✨ Key Features

* **Role-Based Access Control (RBAC):** Dedicated interfaces and workflows for both **Patients** and **Doctors**.
* **Chronic Disease Categories:** Specialized sections for Cancer, Alzheimer's, Liver Failure, Lung Diseases, Bone Marrow Disorders, and Neurological conditions.
* **Doctor Dashboard & Content Management:** Physicians can publish, edit, and manage medical articles and educational videos directly from the app.
* **Real-Time Consultations:** Instant messaging, voice, and video call capabilities connecting patients with healthcare professionals.
* **Subscription & Alerts:** Patients can subscribe to specific disease categories to receive tailored updates and medical guidance.
* **Secure Authentication:** Complete user authentication system with email verification and profile management powered by Firebase Auth.

---

## 📱 UI Gallery (App Screens)

### Patient Journey & Medical Categories
| Login | Registration (Role) | Patient Home | Categories | Disease Details |
| :---: | :---: | :---: | :---: | :---: |
| <img src="screenshots/login.png" width="160"/> | <img src="screenshots/register.png" width="160"/> | <img src="screenshots/patient_home.jpg" width="160"/> | <img src="screenshots/categories.jpg" width="160"/> | <img src="screenshots/disease_details.jpg" width="160"/> |

### Doctor Dashboard, Consultations & Profile
| Doctor Home | Create Content | Doctor Search & Messages | Live Chat | User Profile |
| :---: | :---: | :---: | :---: | :---: |
| <img src="screenshots/doctor_home.jpg" width="160"/> | <img src="screenshots/create_content.png" width="160"/> | <img src="screenshots/messages.png" width="160"/> | <img src="screenshots/chat.png" width="160"/> | <img src="screenshots/profile.png" width="160"/> |

> 📂 **[View All 35+ App Screens (Full UI Gallery)](./screenshots)**

---

## 🛠️ Tech Stack & Architecture

* **Framework:** Flutter (Dart)
* **Backend & Database:** Firebase (Cloud Firestore, Firebase Auth, Firebase Storage)
* **Architecture:** MVC / Clean Modular Structure (`controller`, `model`, `view`, `firebase`)
* **Responsive Design:** Built with `flutter_screenutil` for pixel-perfect scaling across all mobile devices.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/dev-obadamarouf/palliative-care-app.git](https://github.com/dev-obadamarouf/palliative-care-app.git)
