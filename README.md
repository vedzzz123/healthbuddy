# **HealthBuddy**

HealthBuddy is a Flutter-based healthcare application designed to simplify medical processes for both patients and doctors. The app integrates essential features like appointment booking, lab test scheduling, medical document management, and an AI chatbot for providing quick medical advice. It serves as a convenient and efficient platform to streamline healthcare services and improve patient-doctor communication.

---

## **Features**
- **Doctor Appointment Booking**: Patients can easily schedule appointments with their preferred doctors.  
- **Lab Test Scheduling**: Simplified process for booking diagnostic tests.  
- **Secure Medical Document Management**: Upload, store, and manage medical prescriptions and reports securely on the cloud.  
- **AI Chatbot for Medical Advice**: Get personalized health suggestions and medication advice without visiting a doctor.  
- **Dual Portals**:
  - **Patient Portal**: For managing appointments, accessing documents, and interacting with the chatbot.
  - **Doctor Portal**: For managing patient schedules, reviewing medical history, and streamlining patient care.

---

## **Technology Stack**
- **Frontend**: Flutter  
- **Backend**: Firebase (Authentication, Realtime Database, and Cloud Storage)  
- **AI Integration**: Dialogflow or a custom NLP model (optional integration)  
- **Tools Used**:  
  - Android Studio for app development  
  - Visual Studio Code for code editing  

---

## **Installation**
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-repo/healthbuddy.git
   cd healthbuddy
   ```

2. **Install Dependencies**:  
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**:  
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add the `google-services.json` file (for Android) and `GoogleService-Info.plist` (for iOS) in their respective folders.

4. **Run the App**:  
   ```bash
   flutter run
   ```

---

## **Usage**
1. **Patient Access**:
   - Register/login using your email or social media accounts.
   - Book appointments or lab tests from the dashboard.
   - Upload medical documents securely to the cloud.
   - Chat with the AI chatbot for instant health advice.

2. **Doctor Access**:
   - Log in to manage patient appointments.
   - Access patients' uploaded medical history.
   - Track and respond to patient queries.

---

## **Challenges**
- Ensuring compatibility across devices and platforms.  
- Training the AI chatbot to provide accurate and reliable health advice.  
- Maintaining data privacy and compliance with regulations like HIPAA.  

---

## **Future Enhancements**
- Adding telemedicine support for video consultations.  
- Integrating wearable device data for real-time health monitoring.  
- Expanding AI chatbot features to include detailed health assessments.  

---


## **License**
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---
