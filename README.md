# ExpenseMate – Personal Budget & Shared Expense Tracking System

ExpenseMate is an Android mobile application designed to help users manage their personal finances and track shared expenses efficiently. It combines offline personal expense management with cloud-based shared expense tracking, allowing users to monitor their spending and manage financial activities in one place.

## ✨ Features

### 1. Personal Expense Management
- Add, edit, and delete personal transactions.
- Categorize income and expenses.
- Track daily and monthly spending.
- Store personal financial data locally using SQLite.
- Access personal expense records offline.

### 2. Shared Expense Management
- Manage shared household expenses.
- Record expenses shared among multiple users.
- Synchronize shared expense information through Firebase Firestore.
- Access shared financial information online.

### 3. User Authentication
- User registration and login.
- Firebase Authentication integration.
- Individual user accounts.
- Secure access to user-specific information.

### 4. Dashboard and Analytics
- View financial summaries.
- Monitor income and expenses.
- Analyze spending patterns.
- Visualize financial information through charts.

### 5. Additional Features
- User preferences and settings.
- Local data persistence.
- Notifications and reminders.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Android application development |
| Android Studio | Development environment |
| XML | User interface design |
| SQLite | Local database management |
| Firebase Authentication | User authentication |
| Firebase Firestore | Cloud-based data storage |
| SharedPreferences | Local preference storage |
| Git & GitHub | Version control |

## 🏗️ Application Architecture

ExpenseMate uses a hybrid data storage approach.

**Local Storage – SQLite**

Personal financial information is stored locally, allowing users to manage their personal expenses without an internet connection.

**Cloud Storage – Firebase Firestore**

Shared expense information is stored in Firebase Firestore, enabling online access and synchronization.

**Authentication – Firebase Authentication**

Firebase Authentication handles user registration and login.

## 📱 Application Screens

The application includes the following screens:

- Login Screen
- Registration Screen
- Home Dashboard
- Personal Transactions
- Add Transaction
- Shared Expenses
- Expense Categories
- Financial Analytics
- User Profile and Settings

## ⚙️ Installation and Setup

### Prerequisites

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Firebase account
- Android emulator or physical Android device

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/ExpenseMate.git
```

### 2. Open the Project

1. Open Android Studio.
2. Select **Open**.
3. Navigate to the cloned ExpenseMate project.
4. Allow Gradle to synchronize.

### 3. Configure Firebase

1. Create a project in the [Firebase Console](https://console.firebase.google.com/).
2. Register your Android application using its package name:

   `com.geethma.expensemate`

3. Download the `google-services.json` configuration file.
4. Place the file inside the app-level directory.
5. Enable Firebase Authentication and configure Firestore.
6. Synchronize the Gradle project.

### 4. Run the Application

1. Connect an Android device or start an emulator.
2. Select the application configuration.
3. Click **Run** in Android Studio.

## 🔐 Data Storage Strategy

| Data | Storage | Access |
|---|---|---|
| Personal transactions | SQLite | Offline |
| Personal expense records | SQLite | Offline |
| Shared expenses | Firebase Firestore | Online |
| User authentication | Firebase Authentication | Online |
| User preferences | SharedPreferences | Local |

## 🚀 Future Improvements

- Advanced financial analytics and visualizations.
- Monthly budget planning.
- Currency conversion using live exchange rates.
- Spending alerts and notifications.
- Improved shared expense settlement management.
- Data backup and synchronization improvements.

## 🎯 Project Objective

The main objective of ExpenseMate is to provide a convenient financial management solution that combines offline personal expense tracking with online shared expense management.

The application aims to improve financial awareness, simplify expense tracking, and help users manage their money more effectively.

## 👩‍💻 Developer

**Geethma Bandara**

BSc (Hons) Electronics and Information Technology  
Faculty of Science  
University of Colombo, Sri Lanka

## 📄 License

This project is developed for educational purposes as part of Mobile Application Development.
