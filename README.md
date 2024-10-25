# Automatic Attendance Marking System using Group Photos

**Institution:** Shri Ramdeobaba College of Engineering & Management, Nagpur  
**Department:** Computer Science & Engineering (AIML)  
**Session:** 2024-2025

## Table of Contents

- [Introduction](#introduction)
- [Motivation](#motivation)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [System Architecture](#system-architecture)
- [Expected Outcome](#expected-outcome)
- [Contributors](#contributors)
- [Codebase Overview](#codebase-overview)

## Introduction

Attendance tracking is a vital part of managing educational institutions, impacting various decisions related to students and staff. Current attendance systems, such as manual roll calls or biometric setups, are often inefficient and prone to errors or manipulation. Our project aims to automate this process using facial recognition technology.

In this system, cameras will be strategically installed in classrooms to capture images of students during lectures. These images will be stored and processed after the class ends to identify the students and mark their attendance automatically. The attendance records will then be securely stored in a database, and teachers and administrators will have access through a user-friendly interface.

## Motivation

The traditional methods of taking attendance are time-consuming and can lead to errors or manipulation (such as proxy attendance). Additionally, some systems may not accommodate the needs of larger classes or special requirements, such as ensuring accuracy for students with special needs or during connectivity issues.

This project aims to resolve these problems by automating attendance marking, ensuring fairness, accuracy, and efficiency without disrupting the class flow.

## Features

- **Automated Attendance Marking**: Image-based facial recognition will automatically mark attendance after each class, with no manual intervention.
- **Strategically Installed Cameras**: Cameras will be placed to capture clear group images of students, covering the maximum number of faces in each class.
- **Batch Processing**: Images will be stored and processed after class sessions end, ensuring accuracy without real-time constraints.
- **Elimination of Proxy Attendance**: Facial recognition ensures that only present students are marked as attended.
- **User-Friendly Interface**: Administrators and teachers will have access to an easy-to-use platform to manage and view attendance records.

## Technology Stack

- **Front-end**: Vite, React.js
- **Back-end**: Node.js, Express.js
- **AI/ML Model API**: Python, FastAPI, OpenCV, dlib, face_recognition
- **Database**: MySQL
- **Security**: JWT, OAuth 2.0

## Proposed Plan of Work

<img src="https://i.ibb.co/wQCm0N7/Automatic-Attendence-system-mini-project-3.jpg" alt="Automatic-Attendence-system-mini-project-3" border="0">

## System Architecture

<img src="https://i.ibb.co/Bycbxqq/Automatic-Attendence-system-mini-project-1.jpg" alt="Automatic-Attendence-system-mini-project-1" border="0">

1. **Image Scheduler**: Captures images at predefined intervals during the class.
2. **Image Storage**: Stores all captured images securely for later processing.
3. **ML Model**: Detects and recognizes faces in the captured images after the class ends.
4. **Attendance Marker**: Matches recognized faces with the student database and marks attendance.
5. **Database**: Stores attendance data and student information securely.
6. **User Interface**: Provides dashboards for students, teachers, and administrators to view and manage attendance records.

## Expected Outcome

- Fully automated attendance tracking based on stored images.
- Accurate face detection and recognition, even in non-ideal classroom conditions.
- Easy access to attendance records for both students and faculty through a web interface.

## Codebase Overview

This repository serves as a master repository for the entire Automatic Attendance Marking System project, comprising three distinct components:

1. **Backend API**: [Backend Repository](https://github.com/Mini-Project-5th-sem-gr10/backend.git)  
   - Built with Node.js and Express.js, this API handles user authentication, attendance management, and database interactions.

2. **Machine Learning Model API**: [ML Model API Repository](https://github.com/Mini-Project-5th-sem-gr10/ml-model-api.git)  
   - Developed using Python and FastAPI, this component processes images captured in classrooms to recognize faces and mark attendance.

3. **Frontend**: [Frontend Repository](https://github.com/Mini-Project-5th-sem-gr10/frontend.git)  
   - Created with Vite and React, the frontend offers a user-friendly interface for administrators and teachers to manage and view attendance records.

## Contributors

- Akshay Chandak
- Aniket Raut
- Ayush Agrawal
- Heet Dhanuka
- Prakhar Pande
