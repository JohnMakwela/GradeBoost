# GradeBoost

An educational mobile application designed to support South African Grade 12 learners with CAPS-aligned learning resources, past examination papers, AI-powered quizzes, and tutor support.

## Project Overview

GradeBoost is an educational mobile application currently under development as part of a university academic project. The application is designed to support Grade 12 (Matric) learners in South Africa, with a main focus on Mathematics and Physical Sciences.

The goal of GradeBoost is to provide learners with different learning resources and study support in one platform. The application combines educational content, past examination papers, digital textbooks, AI-assisted quizzes, learner progress tracking, and access to tutors to help learners prepare for their examinations.

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

* Digital Library containing educational resources.
* CAPS-aligned digital textbooks and study guides.
* Access to past examination papers and memorandums.
* Study resources and subject formula sheets.
* PDF uploading and text extraction for learning resources.

### AI-Powered Learning and Quizzes

* AI-generated adaptive quizzes.
* Easy, Medium, and Hard quiz difficulty levels.
* Personalised quizzes based on learner performance.
* Weak-topic detection to identify areas where learners may need more practice.
* Quiz history and learner performance tracking.
* AI-assisted learning support.
* Backend fallback and local Android quiz support.

### Learner Progress and Academic Support

* Learner progress tracking.
* Learner achievements and statistics.
* Academic performance information.
* APS Predictor to help learners estimate their potential Admission Point Score.

### Notifications

* Booking and system notifications.
* Notification settings and preferences.

### Administration and System Management

* Admin user management.
* Digital resource management.
* System statistics and analytics.

## Project Goal

GradeBoost aims to bring learning resources, personalised study support, examination preparation, and access to tutors together in one platform to help South African Grade 12 learners improve their learning experience and prepare for their academic goals.

## Project Status

**Status:** In Development

GradeBoost is currently under development as part of a university academic group project. The development team is working on improving the application's learning resources, AI-powered features, tutor functionality, learner support, and backend services.

The project is not yet complete, and some features are still being developed and tested. The team continues to work on improving the application and adding new functionality.

## Technologies and Tools

GradeBoost is being developed using Java and different Android and backend technologies. The main technologies and tools used in the project are listed below.

### Programming Languages and Data Formats

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
* **Activity Result API** – Used when selecting files such as PDF learning resources and profile images from the Android device.

### Backend Development

* **Spring Boot** – Used to develop the GradeBoost backend.
* **Spring Web / Spring MVC** – Used to create REST API endpoints that allow the Android application to communicate with the backend.
* **Apache Tomcat** – Used as the embedded web server for the Spring Boot backend.
* **Jackson** – Used to process JSON data between Java objects and JSON format.
* **Java HTTP Client** – Used by the backend to communicate with external HTTP services.

### AI and Adaptive Quiz System

* **OpenAI Responses API** – Integrated into the backend to support live AI-generated quizzes.
* **Adaptive Quiz Generation** – Used to generate quizzes based on information such as learner performance, weak topics, subject, and selected learning resources.
* **Quiz Difficulty Levels** – Supports Easy, Medium, and Hard quiz difficulty levels.
* **Weak Topic Detection** – Used to identify topics where learners may need more practice.
* **Backend Fallback Quiz System** – Provides adaptive quiz generation when the live AI service is unavailable.
* **Local Android Quiz System** – Provides quiz functionality when the Android application cannot connect to the backend.

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

## My Role and Contributions

I am part of the development team working on GradeBoost as part of our university academic project. I serve as the **Group Leader** and contribute to the development of the application across both the **Frontend and Backend**.

As the Group Leader, my responsibilities include:

* Assigning roles and tasks to group members.
* Coordinating the development work of the team.
* Monitoring the progress of tasks and helping the team stay on track.
* Communicating with group members about their responsibilities and progress.
* Working with team members to identify and solve problems during development.
* Helping the team plan and organise the different parts of the application.

As a developer, I have contributed to different areas of the GradeBoost application, including:

* User registration and login functionality.
* Role-based access for Learners, Tutors, and Administrators.
* Learner, Tutor, and Admin dashboards.
* User and Tutor profile functionality.
* Tutor search and discovery.
* Tutor booking and booking management.
* Tutor-hosted learning sessions and learner registration.
* Attendance tracking using attendance codes.
* Digital Library and learning resources.
* Digital textbooks, study guides, past examination papers, and memorandums.
* PDF uploading and text extraction.
* AI-powered and adaptive quiz functionality.
* Quiz difficulty levels and personalised quizzes.
* Weak-topic detection and learner performance tracking.
* Quiz history, learner progress, achievements, and statistics.
* APS Predictor functionality.
* Notifications and notification settings.
* Admin user and digital resource management.
* Spring Boot backend development.
* REST API development and communication between the Android application and backend.
* SQLite database development and data management.
* Integration of AI services and development of fallback quiz systems.

Working on GradeBoost has given me practical experience in Java, Android development, backend development, REST APIs, databases, AI integration, and software development.

The project has also helped me improve my leadership, communication, teamwork, problem-solving, task delegation, and project management skills. Since the project is still in development, I continue to work with my team to improve the application and implement new features.

## Project Structure

GradeBoost is divided into different parts that work together to provide the main functionality of the application.

### Android Application

The Android application is the main part of the system that learners, tutors, and administrators interact with. It provides the user interface and allows users to access the different features of GradeBoost.

The Android application includes:

* User registration and login.
* Learner, Tutor, and Admin dashboards.
* User and Tutor profiles.
* Digital Library and learning resources.
* Tutor search and booking.
* Learning sessions and attendance.
* AI-powered and adaptive quizzes.
* Learner progress and quiz history.
* Notifications and other user settings.

### Spring Boot Backend

The Spring Boot backend handles communication between the Android application and backend services. It provides REST APIs that allow the Android application to send and receive data.

The backend is responsible for features such as:

* Processing requests from the Android application.
* Managing learning resources.
* Handling PDF uploads and text extraction.
* Supporting adaptive quiz generation.
* Communicating with external AI services.
* Providing fallback quiz functionality when the live AI service is unavailable.

### SQLite Database

GradeBoost uses SQLite as a local database for storing application data. The database is used to manage information such as:

* Users and user roles.
* Learner and Tutor profiles.
* Tutor bookings.
* Learning sessions and registrations.
* Attendance records.
* Quiz history and learner performance.
* Notifications.
* Digital Library resources.

### AI and Adaptive Quiz System

GradeBoost includes an AI-powered quiz system that is designed to provide learners with personalised quizzes.

The system can consider information such as:

* Learner performance.
* Weak topics.
* Selected subject.
* Learning resources.
* Quiz difficulty levels.

The application also includes fallback quiz systems to allow quiz functionality to continue when the live AI service or backend is unavailable.

### System Communication

The main parts of GradeBoost communicate with each other through REST APIs and JSON data.

The general flow is:

**Android Application → Spring Boot Backend → Database / AI Services**

The backend processes requests from the Android application and communicates with the required services before returning the results to the user.
