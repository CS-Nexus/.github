# NEXUS — VR Emergency Response Training Platform

Welcome to the Nexus organization!  
Nexus is an innovative multi-platform system that leverages immersive Virtual Reality, mobile applications, AI, and gamification to educate users on how to respond effectively to emergency situations.

---

## Project Structure

This GitHub organization is composed of the following main repositories:

| Module         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| [`Frontend`](https://github.com/CS-Nexus/Frontend)   | Web dashboard for admins/facilitators to monitor users, manage scenarios, and view analytics. |
| [`Backend`](https://github.com/CS-Nexus/Backend)     | ASP.NET Core API (JWT Auth, OTP, Stripe payments, SignalR, EF Core, Swagger) powering all services. |
| [`Mobile App`](https://github.com/CS-Nexus/Flutter)       | Flutter mobile app for users to track progress, access scenarios, use burn detection & chatbot. |
| [`Game`](https://github.com/CS-Nexus/Unity)               | Unity-based VR emergency simulation game with scenarios like home fires, factory accidents, and brake failures. |
| [`AI`](https://github.com/CS-Nexus/AI)               | Python + TensorFlow skin burn classification API (deployed with Flask + TFLite). |
| [`3D Models`](https://github.com/CS-Nexus/Models)   | Blender-based 3D models used in the VR game, including environments and tools. |

---

## Key Features

- Realistic VR emergency training scenarios (home, factory, car)
- Cross-platform mobile application with subscriptions and user progress
- AI burn detection via mobile camera
- Stripe-powered payment and subscription system
- Real-time leaderboard and achievements with SignalR
- Secure backend with JWT, OTP & custom middleware
- Educational + gamified design for better engagement

---

## Technologies Used

- Backend: ASP.NET Core 8, Entity Framework Core, SQL Server, Stripe, SignalR
- Frontend: Angular
- Mobile: Flutter + Dart
- VR: Unity (C#), XR Toolkit
- AI: Python, TensorFlow, EfficientNet, Flask
- 3D Modeling: Blender

---

## Repository Setup Example

Each subfolder or repo has its own README with setup instructions. For example:

nexus-backend

- Run dotnet run on Nexus.Api
- Swagger available at http://localhost:8080/swagger
- EF Core for DB, Stripe integrated, SignalR enabled

nexus-mobile

- Flutter project using Clean Architecture
- Supports Android & iOS
- Integrated with backend APIs and burn detection

nexus-vr

- Unity project (XR setup with Oculus Quest 2)
- Extinguisher mechanics, fire handling, game logic
- C# codebase with interactive scenarios

---

## Team Members

- Ihab Mahmoud Elgarba
- Ahmed Mohamed Galal
- Esraa Morsii Morsii
- Amera Mahmoud Elbassal
- Eman Mohamed Khater
- Gamal Mohamed Ali
- Amr Ahmed Zakaria
- Omar Tarek Elsayed
- Nabil Ibrahim Abdullah
- Muhammad Mustafa Issa

Supervised by:  
👨‍🏫 Dr. Mohammed Hagag  
👨‍💻 Eng. Amr Eledkawy

---

## Documentation

For full system documentation, refer to our thesis document:  
NEXUS Virtual Reality Emergency Response Training Simulator (2024-2025)

---

## Contact

If you’d like to collaborate, suggest ideas, or report issues, feel free to open an issue or reach out through the Discussions tab!

---

> “NEXUS brings immersive learning and real-life readiness — bridging technology and safety.”
