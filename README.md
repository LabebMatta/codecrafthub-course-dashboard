# 🚀 CodeCraftHub - Developer Learning Tracker

A beginner-friendly REST API built with **Java Spring Boot** that helps developers
track courses they want to learn. Data is stored in a simple JSON file — no database
setup needed.

```
┌─────────────────────────────────────────────────────────┐
│                     CodeCraftHub                        │
│                                                         │
│   "Track what you learn. Finish what you start."        │
│                                                         │
│   ┌─────────┐   ┌──────────┐   ┌───────────────┐       │
│   │   Add   │──▶│  Track   │──▶│   Complete!   │       │
│   │ Courses │   │ Progress │   │   🎉 🎉 🎉    │       │
│   └─────────┘   └──────────┘   └───────────────┘       │
└─────────────────────────────────────────────────────────┘
```

---

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Running the Application](#-running-the-application)
- [API Documentation](#-api-documentation)
  - [Create a Course](#1--create-a-course)
  - [Get All Courses](#2--get-all-courses)
  - [Get Course by ID](#3--get-course-by-id)
  - [Update a Course](#4--update-a-course)
  - [Delete a Course](#5--delete-a-course)
- [Sample Workflow](#-sample-workflow)
- [Project Structure](#-project-structure)
- [Understanding the Data File](#-understanding-the-data-file)
- [Troubleshooting](#-troubleshooting)
- [Learning Resources](#-learning-resources)

---

## ✨ Features

|
 Feature                   
|
 Description                                         
|
|
---------------------------
|
-----------------------------------------------------
|
|
**
Full CRUD Operations
**
|
 Create, Read, Update, and Delete courses            
|
|
**
JSON File Storage
**
|
 No database needed — data lives in 
`courses.json`
|
|
**
Input Validation
**
|
 Rejects blank fields and invalid status values      
|
|
**
Auto-generated Fields
**
|
 IDs and timestamps are created automatically        
|
|
**
Error Handling
**
|
 Clear error messages for every type of bad request   
|
|
**
Beginner-Friendly
**
|
 Detailed comments explain every piece of code       
|

### Course Status Flow

```
┌─────────────┐        ┌──────────────┐        ┌─────────────┐
│ Not Started  │──────▶ │ In Progress   │──────▶ │  Completed  │
│             │        │              │        │   🎓        │
└─────────────┘        └──────────────┘        └─────────────┘
     (new course)        (started learning)       (finished!)
```

---

## 🛠 Tech Stack

|
 Technology    
|
 Version 
|
 Purpose                                    
|
|
---------------
|
---------
|
--------------------------------------------
|
|
 Java          
|
 17+     
|
 Programming language                       
|
|
 Spring Boot   
|
 3.2.0   
|
 Web framework for building REST APIs       
|
|
 Jackson       
|
 Auto    
|
 Converts Java objects to/from JSON         
|
|
 Maven         
|
 3.6+    
|
 Manages project dependencies and builds    
|
|
 Embedded Tomcat
|
 Auto   
|
 Built-in web server (no setup needed)      
|

---

## 📦 Prerequisites

Before starting, make sure you have these installed on your computer:

### 1. Java 17 or higher

```bash
# Check if Java is installed and which version you have
java -version
```

**Expected output (version 17 or higher):**
```
openjdk version "17.0.9" 2023-10-17
```

**If Java is NOT installed:**
- **Windows/Mac/Linux:** Download from [https://adoptium.net](https://adoptium.net)
- **Mac
