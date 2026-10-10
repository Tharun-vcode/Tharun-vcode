# Tharun Vijayakumar

### Engineering Undergraduate | Backend Development | API Design | Database Systems

I am an Electronics & Communication Engineering undergraduate at **PSG Institute of Technology and Applied Research**, interested in building reliable, scalable, and practical software systems.

My primary interests are **backend development, database systems, API design, and software engineering**. I enjoy understanding how systems work behind the interface — from designing database schemas and REST APIs to implementing authentication, authorization, file storage, and integrations with external services.

I also work with **AI/ML and LLM-based applications**, particularly when they can be integrated into practical software products.

---

## About Me

* Pursuing **B.E. in Electronics & Communication Engineering** at PSG Institute of Technology and Applied Research
* Interested primarily in **Software Development and Backend Engineering**
* Experience building backend applications using **Node.js, Express.js, PostgreSQL, Prisma, Sequelize, Flask, and SQLite**
* Experience designing and integrating **REST APIs**
* Familiar with authentication and authorization using **JWT, bcrypt, HMAC-based verification, and role-based access control**
* Interested in **database design, API architecture, system reliability, and scalable application development**
* Worked as a **Software Developer Intern at Niftrix Technologies**
* Built and contributed to projects involving **cloud file storage, AI-powered agriculture, financial applications, weather applications, and backend APIs**
* Comfortable working with **Java, C, SQL, Python, and JavaScript**
* Currently strengthening my knowledge of **Data Structures and Algorithms, DBMS, Operating Systems, Computer Networks, and Software Engineering**

---

## Technical Skills

### Programming Languages

`Java` `C` `C++` `Python` `SQL` `JavaScript`

### Backend Development

`Node.js` `Express.js` `Flask` `REST APIs` `API Design` `JWT` `bcrypt`

### Databases

`PostgreSQL` `SQLite` `Prisma` `Sequelize`

### Authentication and Security

`JWT Authentication` `Role-Based Access Control` `HMAC-SHA256` `Password Hashing` `API Rate Limiting` `Secure API Design`

### AI / Machine Learning

`CNN` `MobileNetV2` `Random Forest` `LLM API Integration` `Prompt-based Applications`

### Tools and Platforms

`Git` `GitHub` `Postman` `VS Code` `Firebase` `Cloudinary` `Azure Blob Storage`

---

# Professional Experience

## Software Developer Intern — Niftrix Technologies

**May 2026 – June 2026**

Worked as part of a backend development team on **Biznex v2**, a Business-as-a-Service gateway designed to connect third-party platforms and communities with enterprise applications.

### Key Contributions

* Worked on the development of a **BCaaS gateway module** using Node.js, Express.js, PostgreSQL, and Sequelize.
* Contributed across multiple development phases, including **schema design, API implementation, integration, testing, and deployment**.
* Designed and implemented backend APIs for third-party platform integration.
* Worked with API specifications and contracts used by multiple engineering teams.
* Implemented authentication and user provisioning workflows for users arriving through partner platforms.
* Designed database structures for maintaining relationships between external platform users and Biznex users.
* Worked with **JWT-based authentication** and secure request verification.
* Implemented request verification using **HMAC-SHA256** and timestamp-based validation.
* Worked with API-level controls such as request limits and security headers.
* Tested and debugged APIs using **Postman** and REST-based workflows.
* Investigated backend issues by tracing requests through routing, validation, authentication, and database layers.
* Collaborated with a three-developer core team through backend reviews and integration discussions.

### Technologies

`Node.js` `Express.js` `PostgreSQL` `Sequelize` `REST APIs` `JWT` `HMAC-SHA256` `Postman`

---

# Featured Projects

## StackDrive

### Secure and Scalable File Management Backend

**Repository:** [StackDrive](https://github.com/Tharun-vcode/Stack_Drive)

StackDrive is a backend-focused file management application designed around secure file storage, user isolation, structured folders, and efficient interaction with cloud object storage.

### Key Features

* User registration and authentication
* JWT-based authentication
* Password hashing using bcrypt
* File upload, download, and deletion
* Hierarchical folder management
* Search, filtering, and sorting
* Pagination for large datasets
* User-level file and folder isolation
* Role-based access control
* Database indexing for improved query performance
* Cloud object storage integration using Cloudinary
* REST API architecture

### Architecture Highlight

Instead of sending entire files through the backend server, StackDrive uses **signed upload URLs** so that clients can upload files directly to object storage.

This reduces unnecessary backend processing and allows the application server to focus on authentication, authorization, metadata management, and API operations.

### Database Design

The application uses PostgreSQL because the system has strong relationships between users, files, and folders.

The database models include:

* Users
* Files
* Folders

Folders support hierarchical organization using a `parent_id` relationship, allowing both root-level and nested folders.

### Technologies

`Node.js` `Express.js` `PostgreSQL` `Prisma` `JWT` `bcrypt` `Cloudinary` `REST APIs` `Postman`

---

# CropCare

### AI-Powered Smart Farming Assistant

**Repository:** [CropCare](https://github.com/Tharun-vcode/CropCare)

CropCare is an AI-IoT platform designed to assist farmers, particularly in rural and low-connectivity environments, with crop health, soil analysis, farming information, and recommendations.

The project combines machine learning, IoT sensors, APIs, and multilingual interaction into a single platform.

### My Technical Contributions

* Developed the **plant disease prediction** component using a CNN-based MobileNetV2 model.
* Worked with a plant disease recognition model trained around the PlantVillage dataset.
* Implemented soil quality analysis using a **Random Forest-based approach**.
* Built fertilizer recommendation functionality based on soil conditions.
* Integrated an LLM-powered farming question-answering chatbot.
* Integrated **Groq LLaMA 3** for low-latency conversational responses.
* Worked on multilingual interaction supporting English and Tamil.
* Integrated external APIs for weather-related information.
* Contributed to the overall integration of the AI components with the application.

### Platform Features

* Plant disease identification
* Soil quality prediction
* Fertilizer recommendations
* AI-powered farming assistant
* Multilingual interaction
* Weather information
* IoT-based soil and environmental monitoring
* Farmer discussion/forum functionality
* Agricultural schemes and information
* Automated notifications

### IoT Components

The system integrates an **ESP32** with:

* Soil moisture sensors
* DHT temperature and humidity sensors

The collected data can be used alongside the AI components to provide more context-aware agricultural recommendations.

### Technologies

`Python` `Streamlit` `CNN` `MobileNetV2` `Random Forest` `LLM APIs` `Groq` `Firebase` `ESP32` `IoT` `OpenWeather API` `Twilio`

### Recognition

* **1st Prize** — Atom 2K26 Project/Research Presentation
* **Special Mention** — Project Expo 2025, PSG Institute of Technology and Applied Research
* Research work presented through academic/project platforms

---

# Other Projects

## CashCoach

A personal finance application focused on tracking and managing financial information.

### Technologies

`Python` `Flask` `SQLite`

---

## MyWeather

A weather application that retrieves and presents weather information through an external weather API.

### Technologies

`Python` `Flask` `SQLite` `REST APIs`

---

# Areas of Interest

### Backend Engineering

I enjoy building the systems behind applications, particularly APIs, authentication flows, database interactions, and service integrations.

### Database Systems

I am interested in relational database design, normalization, indexing, query optimization, and designing schemas that accurately represent application requirements.

### API Development

I enjoy designing REST APIs with clear request/response structures, authentication mechanisms, validation, and integration with external services.

### Software Engineering

I am interested in writing maintainable code, debugging production-like issues, understanding system behavior, and designing applications around practical requirements.

### Artificial Intelligence

I am interested in applying machine learning and LLMs to practical applications rather than treating AI as an isolated component.

---

# GitHub Projects

Some of the projects I have worked on include:

| Project                                                   | Description                       | Technologies                         |
| --------------------------------------------------------- | --------------------------------- | ------------------------------------ |
| [StackDrive](https://github.com/Tharun-vcode/Stack_Drive) | Secure file management backend    | Node.js, Express, PostgreSQL, Prisma |
| [CropCare](https://github.com/Tharun-vcode/CropCare)      | AI-powered smart farming platform | Python, Streamlit, ML, IoT           |
| CashCoach                                                 | Personal finance application      | Flask, SQLite                        |
| MyWeather                                                 | Weather information application   | Flask, SQLite, APIs                  |

---

# Education

## PSG Institute of Technology and Applied Research

**B.E. Electronics & Communication Engineering**

**2023 – 2027**

Current GPA: **8.16 / 10**

My degree has given me a foundation in engineering while my projects and self-directed learning have allowed me to focus strongly on software development and backend engineering.

---

# Connect With Me

**GitHub:**
https://github.com/Tharun-vcode

**LinkedIn:**
https://www.linkedin.com/in/tharun-vijayakumar-440658322/

**Email:**
tharunblr62@gmail.com

---

## GitHub

I use this profile to document my projects, experiments, and continued learning as I work toward becoming a stronger software engineer.
