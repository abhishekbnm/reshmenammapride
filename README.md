# Reshme Namma Pride - Smart Sericulture Monitoring

Reshme Namma Pride is a specialized Android application designed to empower silkworm farmers with data-driven climate management. By monitoring temperature and humidity relative to the specific instar stage of the silkworms, the app provides actionable advice to ensure a healthy and high-yield harvest.

## 🚀 Key Features
- **Instar-Specific Monitoring**: Custom climate logic for all 5 stages of silkworm growth.
- **Smart Advice Engine**: Instant recommendations (Ventilation, Water Spraying, Lime Powder) based on real-time data.
- **Batch Tracking**: Manage multiple silkworm batches simultaneously with Room database persistence.
- **Visual Dashboard**: Color-coded dials (Green/Orange/Red) for immediate status awareness.
- **Historical Analysis**: View past climate logs to identify environmental patterns.

## 🛠️ Technical Stack
- **Language**: Kotlin
- **UI**: Jetpack Compose (Material 3)
- **Architecture**: MVVM (Model-View-ViewModel)
- **Database**: Room Persistence Library
- **Dependency Injection**: Manual (Repository Pattern)
- **Navigation**: Navigation Compose
- **Concurrency**: Kotlin Coroutines & StateFlow

## 📝 Setup Instructions
1. **Prerequisites**: Android Studio Ladybug (or newer) and Android SDK 35+.
2. **Clone/Open**: Open the project in Android Studio.
3. **Build**: Run a Gradle Sync and build the `:app` module.
4. **Run**: Deploy to an emulator or physical device running Android 8.0 (API 26) or higher.

---

## 🔮 Future Enhancement Ideas

### 1. IoT Sensor Integration
- **Automated Monitoring**: Connect Bluetooth or Wi-Fi enabled DHT11/DHT22 sensors to feed temperature and humidity data directly into the app without manual entry.
- **Real-time Alerts**: Push notifications if sensors detect a "Danger" state while the app is in the background.

### 2. Cloud Synchronization
- **Firebase Integration**: Sync batch data to the cloud so farmers can access their records from multiple devices.
- **Expert Consultations**: Allow farmers to share their climate history with sericulture experts for remote diagnosis.

### 3. Image Recognition (AI)
- **Health Check**: Use the camera to scan silkworms. An AI model can detect early signs of diseases (like Grasserie or Flacherie) based on visual symptoms.
- **Growth Tracking**: Automatically estimate the instar stage by analyzing the size and color of the silkworms in a photo.

### 4. Market & Weather Integration
- **Price Tracking**: Real-time integration with local Cocoon Market prices.
- **Weather Forecasts**: Warn farmers of upcoming heatwaves or heavy rains that might affect the rearing house environment.

### 5. Multi-language Support
- **Localization**: Full support for Kannada and other regional languages to make the app accessible to all local farmers.

---
*Developed as a smart solution for the Pride of Sericulture.*
