🌱 Hydroponics Monitoring App

This project is a mobile & web application designed for farmers using hydroponic systems. With the help of Bluetooth-enabled sensors, the app provides real-time monitoring of plant growth conditions and tools to manage plants effortlessly.

Farmers can track live data, add/remove plants, and receive actionable insights to keep their crops healthy and productive.

🚀 Features

📡 Real-Time Sensor Monitoring
Get instant readings from Bluetooth sensors on:

pH Levels

Temperature

Humidity

Sunlight Intensity

🌿 Plant Management

Add new plants to the system

Remove plants when harvested or replaced

View plant-specific sensor history

🛠 Smart Suggestions

Diagnose issues like low pH, heat stress, or inadequate light

Receive simple, farmer-friendly solutions on how to fix them

📊 Data Visualization
Graphs & dashboards to analyze plant health over time

🧑‍💻 Tech Stack

Frontend: React Native (Mobile), React (Web)

Backend: Node.js with Express

Database: Firebase / MongoDB

Connectivity: Bluetooth Low Energy (BLE)

State Management: Redux / Recoil

🏗 Architecture

The app follows a modular architecture separating domain logic from sensor integrations:

Domain Layer: Plant entities, health status, suggestions engine

Adapter Layer: Bluetooth communication & API handlers

Framework Layer: Mobile & Web interfaces

This ensures scalability, testability, and clear separation of concerns.

📂 Directory Structure
/packages
├─ mobile          # React Native app
│  ├─ components
│  ├─ hooks
│  ├─ services     # Bluetooth services
│  └─ screens
├─ web             # React web app
│  ├─ components
│  ├─ hooks
│  └─ pages
├─ server          # Node.js backend
│  ├─ controllers
│  ├─ models
│  └─ routes
└─ shared          # Common DTOs, utilities

⚙️ Setup & Installation
1. Clone Repository
git clone https://github.com/your-org/hydroponics-monitoring.git
cd hydroponics-monitoring

2. Install Dependencies
yarn install

3. Start Mock Server
yarn run mock-server

4. Run Web App
yarn run web

5. Run Mobile App

iOS

cd packages/mobile/ios
pod install
cd ../../../
yarn run ios


Android

yarn run android

📸 Screenshots

(Add sensor dashboard, plant list, and health suggestions screenshots here)

📌 Version

v1.0.0 – Initial release with real-time monitoring & plant management.

🤝 Contribution

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or raise an issue to improve the app.
