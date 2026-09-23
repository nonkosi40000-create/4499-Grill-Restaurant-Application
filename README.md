# 4499-Grill-Restaurant-Application
Project Overview

4499GRILL is a premium, wood-fired food ordering application designed to provide a seamless dining experience from discovery to delivery. The app features a robust menu management system, real-time order tracking, an AI-powered chat assistant for personalized recommendations, and a role-based dashboard system for Customers, Workers, and Managers. By integrating community features and a streamlined cart management system, 4499GRILL bridges the gap between traditional grilling and modern digital convenience.

Tech Stack & SDKs

The application is built using the Android SDK with Kotlin, leveraging modern UI components like Material Design 3 and ConstraintLayout for a responsive experience. We utilized the Firebase SDK (BOM 33.9.0) as our primary backend infrastructure. Firebase was selected for its powerful suite of tools: Firestore provides a real-time NoSQL database for instant order and chat updates, Firebase Auth ensures secure user management, and Firebase Storage handles high-quality food imagery. This serverless approach allows the app to scale efficiently while maintaining low latency for critical restaurant operations.

Security & Configuration

For security reasons, this project does not contain hardcoded API keys. The application is directly linked to the Firebase Console via the google-services plugin. This integration allows the Firebase SDK to automatically manage authentication and service handshakes using the internal project configuration. By following this standard Android development practice, we ensure that sensitive credentials remain protected and that the app communicates securely with its backend services without exposing private keys in the source code.
