# Passport Automation System

## 📝 Introduction

The **Passport Automation System** is a software tool developed to streamline the process of applying for a passport. The system eliminates the traditional paper-based workflow and replaces it with a centralized, digital process that involves applicants, passport administrators, regional administrators, and police authorities.

This project demonstrates how software tools like **ArgoUML** can be used for modeling real-world systems using **UML diagrams**.

---

## ⚙️ Tools Used

- **ArgoUML** – For designing UML diagrams (Use Case, Class, Sequence, Activity, etc.)
- **Java (Swing GUI)** – For implementing the user interface
- **MySQL/Flat-file Database** – For storing user data and verification information
- **Java IDE (like NetBeans or Eclipse)** – For development
- **Paint/Online tools** – For UML diagram visualization if required

---

## 🚀 How It Works

1. **User Login:** The applicant logs into the system using a username and password.
2. **Application Submission:** The user enters and submits their personal details via the form.
3. **Verification:** The passport administrator and police verify the submitted information.
4. **Regional Admin Review:** After successful verification, the regional administrator approves the request.
5. **Passport Issuance:** Once approved, the system generates the passport and notifies the user.
6. **Status Check:** Applicants can check the status of their application anytime via the system.

---

## 📊 UML Diagrams

### ✅ Use Case Diagram

This diagram outlines the interaction between different actors (Applicant, Police, Passport Administrator, and Regional Administrator) and the system.

![Use Case Diagram](Screenshot_2025-05-13_195846.png)

---

### ✅ Class Diagram

This diagram shows the main classes, their attributes, and methods, including relationships between the `Applicant`, `Police`, `PassportAdministrator`, `RegionalAdministrator`, and the `Database`.

![Class Diagram](Screenshot_2025-05-13_200002.png)

---

## 🧑‍💻 User Interface (UI)

Below is a screenshot of the application interface, showing login, detail submission, status check, and confirmation.

![User Interface](Screenshot_2025-05-13_195936.png)

---
