# 🚀 BengalVPN - High-Performance VPN Solution (Android & Laravel)

BengalVPN is a professional-grade VPN ecosystem featuring a powerful **Laravel 11 Admin Panel** and a **Native Android Application** built with Java. It is designed for maximum speed, security, and effortless management with a built-in auto-installation wizard.

---

## 🌐 Live Demo & Documentation
         🌐https://futuretechbd.net/demo/

---

## ✨ Key Features

### 📱 Android App Features
- **One-Tap Connection:** Simple and intuitive UI for global server connection.
- **Real-time Speed Meter:** Integrated download and upload speed monitoring.
- **Protocol Support:** Supports high-speed OVPN protocols.
- **Subscription Management:** Offline payment submission (Bkash/Nagad/Rocket).
- **Ad-Free Experience:** Premium users enjoy an environment without ads.
- **AdMob Integration:** Monetize free users with Banner and Interstitial ads.

### 🛡️ Admin Panel Features (Laravel 11)
- **Auto-Installation Wizard:** Setup your database and admin account in 2 minutes.
- **Server Management:** Add/Edit/Delete VPN nodes and upload `.ovpn` files.
- **Payment Request Handling:** Review and approve subscription requests manually.
- **Dynamic Ads Config:** Control AdMob visibility and IDs directly from the dashboard.
- **Secure API:** Fully encrypted communication between App and Server.

---

## 🛠️ Technology Stack
- **Mobile:** Android (Java/Kotlin), MVVM Architecture, Retrofit, OpenVPN SDK.
- **Backend:** Laravel 11, PHP 8.2+, MySQL 8.0.
- **Infrastructure:** Ansible (Automation), cPanel/Shared Hosting compatible.

---


## 🚀 Fast Installation

### 1. Backend Setup
1. Upload the `Backend` folder files to your server.
2. Navigate to `yourdomain.com/install`.
3. Follow the wizard to configure the database and admin user.

### 2. Android App Setup
1. Open the project in **Android Studio**.
2. Change the `BASE_DOMAIN` in `ApiClient.java`:
   ```java
   public static final String BASE_DOMAIN = "[https://yourdomain.com/]
