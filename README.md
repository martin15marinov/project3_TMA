Name of the project: Travel Memory Map

What is about: MemoryMap is a mobile application that allows users to save personal memories on a map. Each memory includes a title, description, image, and geographic location.

Complexity: high

Features:
Google Maps integration with marker placement
Add/Edit memory with validation
Memory list with search functionality
Detailed memory view with image and coordinates
Local storage using Room (CRUD operations)
Search by title/description
Offline-first synchronization with remote API
Remote backend integration (Retrofit)
State management using ViewModel + StateFlow
Dependency Injection with Hilt

How to build:
Run the following command from the project root: .\gradlew.bat assembleDebug
The APK will be generated in: app/build/outputs/apk/debug/app-debug.apk

API Keys setup:
This project uses Google Maps API.
Before building the project, create or edit the `local.properties` file in the project root and add: id="8sd2ka"MAPS_API_KEY=YOUR_REAL_GOOGLE_MAPS_KEY
Note:
The `local.properties` file is excluded from version control (`.gitignore`)
Your API key will NOT be committed to the repository

