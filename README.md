# GradeBoost
An educational mobile application designed to support South African Grade 12 learners with CAPS-aligned learning resources, past examination papers, AI-powered quizzes, and tutor support.

## Project Overview

GradeBoost is an educational mobile application currently under development as part of a university academic project. The application is designed to support Grade 12 (Matric) learners in South Africa, with a primary focus on Mathematics and Physical Sciences.

The goal of GradeBoost is to provide learners with accessible digital learning resources and personalised study support in one platform. The application combines educational content, past examination papers, AI-powered quizzes, AI-assisted learning support, and access to tutors to help learners prepare for their examinations.

## Key Features

### User Management and Access Control

* User registration and login.
* Role-based access for Learners, Tutors, and Administrators.
* Dedicated dashboards for Learners, Tutors, and Administrators.
* Learner and Tutor profile management.
* Password recovery and "Remember Me" login functionality.

### Tutor Management and Learning Sessions

* Tutor search and discovery.
* Tutor profiles and availability.
* Tutor booking system with booking management and status tracking.
* Tutor-hosted learning sessions.
* Learner session registration.
* Attendance tracking using attendance codes.

### Digital Learning Resources

* Digital library containing educational resources.
* CAPS-aligned digital textbooks and study guides.
* Access to past examination papers and memorandums.
* Study resources and subject formula sheets.
* PDF upload and text extraction capabilities.

### AI-Powered Learning and Quizzes

* AI-generated adaptive quizzes for learners.
* Easy, Medium, and Hard quiz difficulty levels.
* Personalized quizzes based on learner performance.
* Weak-topic detection to identify areas requiring additional study.
* Quiz history and performance tracking.
* AI-assisted learning support.
* Backend fallback and offline quiz support.

### Learner Progress and Academic Support

* Learner progress tracking.
* Learner achievements and statistics.
* Academic performance insights.
* APS Predictor to help learners estimate their potential Admission Point Score.

### Notifications

* Booking and system notifications.
* Notification settings and preferences.

### Administration and System Management

* Admin user management.
* Digital resource management.
* System statistics and analytics.

### Project Goal

GradeBoost aims to bring learning resources, personalized AI-assisted study support, examination preparation, and access to tutors together in a single platform to help South African Grade 12 learners prepare for their academic goals.

## Technologies and Tools

GradeBoost is being developed using Java and several Android and backend technologies. The main technologies and tools used in the project are listed below.

### Programming Languages

* **Java** – The main programming language used to develop the Android application and Spring Boot backend.
* **XML** – Used to design the user interfaces of the Android application.
* **SQL** – Used to work with and manage data stored in the SQLite database.
* **JSON** – Used to exchange data between the Android application, backend, and AI services.

### Android Development

* **Android SDK** – Used to develop the Android mobile application.
* **Android Studio** – Used to write code, design interfaces, build, test, and debug the Android application.
* **AndroidX AppCompat** – Used in the development of Android activities and to support compatibility across different Android versions.
* **RecyclerView** – Used to display lists of information such as tutors, bookings, notifications, learning resources, and quiz history.
* **ConstraintLayout** – Used to organise and position components in Android layouts.
* **Material Components** – Used to create the user interface and maintain a consistent design throughout the application.
* **SharedPreferences** – Used to store information such as login sessions, "Remember Me" settings, notification preferences, and other user settings.
* **SQLite** – Used as the local database for storing application data on the Android device.
* **SQLiteOpenHelper** – Used to create and manage the SQLite database.
* **CircleImageView** – Used to display user profile images in a circular format.

### Backend Development

* **Spring Boot** – Used to develop the GradeBoost backend.
* **Spring Web / Spring MVC** – Used to create REST API endpoints that allow the Android application to communicate with the backend.
* **Apache Tomcat** – Used as the embedded web server for the Spring Boot backend.
* **Jackson** – Used to process JSON data between Java objects and JSON format.
* **Java HTTP Client** – Used by the backend to communicate with external services.

### AI and Adaptive Quizzes

* **OpenAI Responses API** – Integrated into the backend to support AI-generated quizzes.
* **Adaptive Quiz Generation** – Used to generate quizzes based on information such as the learner's performance, weak topics, subject, and selected learning resources.
* **Quiz Difficulty Levels** – Supports Easy, Medium, and Hard difficulty levels.
* **Weak Topic Detection** – Used to identify topics where learners may need more practice.
* **Backend Fallback Quiz System** – Provides quiz generation when the live AI service is not available.
* **Local Android Quiz System** – Provides quiz functionality when the application cannot connect to the backend.

### Learning Resources and PDF Processing

* **PDF Upload and Processing** – Used to upload learning resources such as past examination papers.
* **PDF Text Extraction** – Used to extract text from uploaded PDF documents for use in the adaptive quiz system.
* **Android Content URIs** – Used to access files selected from the Android device.

### Development Tools

* **Gradle** – Used to build the Android project and manage dependencies.
* **Gradle Kotlin DSL** – Used for Gradle build configuration files.
* **JDK (Java Development Kit)** – Used to compile and run Java applications.
* **IntelliJ IDEA** – Used to develop and run the Spring Boot backend.
* **Pixel 7 Android Emulator** – Used to test the Android application during development.
* **Windows PowerShell** – Used for testing the backend and REST API endpoints.
* **cURL** – Used to send HTTP requests when testing the backend.
* **Invoke-RestMethod** – Used to test REST API endpoints and check backend responses.

### AI Integration Status

The OpenAI AI quiz generation feature has been integrated into the GradeBoost backend. However, the live AI feature is currently unavailable during testing because of API usage and credit limitations.

To make sure the quiz feature can still work, GradeBoost has a fallback system:

**Live OpenAI AI → Backend Adaptive Quiz → Local Android Quiz**

This means that if the live AI service is unavailable, the backend can generate a fallback quiz. If the backend is also unavailable, the Android application can use its local quiz functionality.

