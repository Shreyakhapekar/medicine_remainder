Medicine Reminder App

A simple Flutter app that helps users remember to take their medicines on time.
Users can add medicines along with dose & schedule a reminder notification.

🎯 Features
🏠 Home Screen

Displays list of added medicines

Shows Name, Dose & Time

Automatically sorts by time (earlier first)

Shows a “No medicines added” placeholder when list is empty

➕ Add Medicine

Add a medicine name, dose, and pick a reminder time

Prevents saving if fields are empty

Orange button for Save (UI requirement)

⏰ Notifications & Alarms

Triggers a notification at the set time

Works even if the app is minimized or in background

Shows medicine name + scheduled time

💾 Local Storage (No backend)

Uses Hive database to store medicines locally

Persists even after phone restarts

🎨 UI Theme (Required)

Primary Color: Teal

Button/Accent: Orange

🧠 State Management

Uses Provider for state updates

UI and business logic kept separate

🛠️ Tech Stack

Flutter

Provider State Management

Hive Local Database

Flutter Local Notifications

Android Alarm Manager

📸 Screenshots / Recording

📌 Add your screen recording in Google Drive and link here
📌 Add screenshots if available

▶️ Getting Started

Clone the repo:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


Install packages:

flutter pub get


Run the app:

flutter run

📦 Build APK
flutter build apk --release


APK will be inside:

build/app/outputs/flutter-apk/

🔐 Permissions Required

Notification permission

Background execution

📁 Folder Structure
lib/
 ├─ models/        // Medicine data model (Hive)
 ├─ providers/     // App state and Hive helpers
 ├─ services/      // Notification + Alarm logic
 ├─ screens/       // Home & Add Medicine UI
 └─ main.dart      // App start + Provider setup

📌 Submission Requirements (Covered)

✔ Teal & Orange theme
✔ Notifications
✔ Local Database
✔ Sorted List UI
✔ APK
✔ Screen recording
✔ GitHub repo public

🙌 Author

Shreya Khapekar
Made for Flutter assignment / academic project
