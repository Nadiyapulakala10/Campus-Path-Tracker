Campus Path Tracker
AI & Verilog Based Real-Time Campus Proximity and Safety System

📌 Overview
Campus Path Tracker is a real-time campus safety and proximity awareness system designed to help students locate friends during partial network failures such as weak signals, one-way communication, or inaudible calls.
The system enables users to search friends using their name or roll number, identify their approximate campus location, and detect nearby known users who can provide immediate assistance.

This project combines:
📡 Real-Time Location Tracking
🧠 AI-Based Decision Making
🔌 Verilog-Based Proximity Logic
🌐 App-Based User Interface
to improve student safety and communication within university campuses.

🚨 Problem Statement
In large university campuses, students often experience partial communication failures caused by weak signal strength, one-way message delivery, or unclear calls. In such situations, users cannot determine the exact location of their friends or identify nearby trusted individuals who can help.
Existing communication applications lack campus-specific proximity awareness and real-time nearby friend detection, creating safety concerns during emergencies or low-network conditions.
Campus Path Tracker addresses this issue by providing intelligent real-time campus visibility and proximity-based assistance.

🎯 Objectives
--> Enable real-time campus location visibility
--> Detect nearby trusted users
--> Provide smart helper recommendations using AI
--> Support communication during low-signal conditions
--> Improve campus safety and emergency response

✨ Features
-->🔍 Search friends by Name / Roll Number
-->📍 Real-time campus block detection
-->👥 Nearby friend identification
-->🧠 AI-based nearest helper suggestion
-->📶 Signal strength monitoring
-->🚨 Emergency alert support
-->🌐 App-based dashboard
-->🔌 Verilog-based proximity processing logic

🧠 AI Integration
The AI module is responsible for intelligent decision-making.
AI Functions
Predict nearest available helper
Estimate user location during weak connectivity
Detect emergency situations
Analyze proximity and movement patterns
Example
User A → 10m away
User B → 30m away
AI Suggestion:
"Best nearby helper: User A"

🔌 Verilog Integration
Verilog is used to simulate hardware-level proximity detection and signal processing.
Verilog Modules
RSSI Signal Processing
Distance Estimation
Proximity Detection
Communication Switching Logic
Example Logic
Strong Signal  → Near
Medium Signal  → Nearby
Weak Signal    → Far

🌐 System Architecture
Mobile Devices
      ↓
GPS / Bluetooth / Wi-Fi
      ↓
Frontend Website
      ↓
Firebase Realtime Database
      ↓
AI Decision Logic
      ↓
Location & Nearby User Output

🛠️ Technologies Used
      Technology	                Purpose
HTML/CSS/JavaScript	       Frontend Development
Firebase	Realtime         Database & Hosting
GPS / Geolocation API	     Live Location Tracking
Bluetooth	                 Proximity Awareness
Verilog	                   Hardware-Level Logic
VS Code	                   Development Environment

📍 How the System Works
1.User logs into the system
2.GPS captures live location
3.Data is stored in Firebase
4.User searches friend by name or roll number
5.System retrieves:
 -->Campus block location
 -->Nearby users
 -->Signal status
6.AI selects nearest helper
7.Alerts are generated if required

📡 Real-Time Location Tracking
The system uses:
-->GPS for accurate positioning
-->Wi-Fi support for indoor accuracy
-->Bluetooth for nearby user detection

📷 Future Enhancements
Indoor navigation
Route guidance
Voice alerts
IoT wearable integration
Machine learning-based movement prediction

