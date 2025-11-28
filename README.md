# 📘 Object Oriented System Analysis & Design (OOSAD)  
### **Resume Building & Job Analyzer System – Case Study Project**

This project was created as part of my **Semester 5 subject CA608 – Object Oriented System Analysis and Design**.  
Throughout the semester, I learned how to model systems using **UML diagrams** such as Use Case, Activity, Class, and Sequence Diagrams.

The selected case-study project is a **Resume Building & Job Analyzer System**, where I designed all core UML diagrams representing system behavior and structure.

---

## 📘 Project Overview

The objective of the system is to allow users to:

- Create resumes using available templates  
- Upload, edit, download, and update CVs  
- Get job suggestions and resume analysis  
- Apply for jobs via integrated platforms  
- Make payments for premium templates  
- View resume advice and statistics  

The system contains multiple actors such as **Admin**, **End User**, **Template Developer**, **Analyst**, **Extension Developer**, and **Bank**.  
(Reference: Case Study Document) :contentReference[oaicite:0]{index=0}

---

## 👥 Actors Involved

- **Admin** – Manage users, roles, statistics, templates  
- **Analyst** – Analyze user activity, manage promotions  
- **End User** – Register, create resumes, download CV, apply for job  
- **Template Developer** – Upload, modify, delete templates  
- **Extension Developer** – Maintain extension tools (e.g., grammar checker)  
- **Bank** – Handles payments and discounts  

(Reference: Use Case Diagram) :contentReference[oaicite:1]{index=1}

---

## 📂 Repository Structure

```
oosad-resume-builder-system/
│── OOSAD_Case_Study.pdf
│── use_case_diagram.pdf
│── activity_diagram.pdf
│── class_diagram.pdf
│── sequence_diagram.pdf
└── README.md
```

---

## 🧩 UML Diagrams Included

### ✔ 1. **Use Case Diagram**
Represents interactions between system actors and functionalities such as:
- Login, Registration  
- Template Uploading/Deleting/Modifying  
- Apply for Job  
- Payment  
- View Statistics  
- Update Resume  
(Use Case Diagram Reference) :contentReference[oaicite:2]{index=2}

---

### ✔ 2. **Activity Diagram**
Describes step-by-step workflow for:
- Login  
- Registration  
- Payment  
- Template Uploading  
- Template Deleting  
- CV Downloading  
- Apply for Job  
(Reference: Activity Diagram) :contentReference[oaicite:3]{index=3}

---

### ✔ 3. **Class Diagram**
Models system structure with classes such as:
- `connection`  
- `registration`  
- `login`  
- `user`  
- `bookappointment`  
- `payment` (with subclasses `credit`, `cash`, `check`)  
- `feedback`  
- `checkstatus`

Shows attributes, methods, and relationships between classes.  
(Reference: Class Diagram) :contentReference[oaicite:4]{index=4}

---

### ✔ 4. **Sequence Diagram**
Shows message flow between components for:
- Login  
- Registration  
- Payment  
- Delete User  
- Download Resume  
- Template Upload/Delete/Modify  
- Apply for Job  
(Reference: Sequence Diagram) :contentReference[oaicite:5]{index=5}

---

## 🎯 Key Functionalities Modeled

From the case-study document and your diagrams, the system supports:

- Login & Authentication  
- Registration & User Management  
- Resume Template Management  
- Update CV & Download Resume  
- Apply for Jobs & Analyze Job Fit  
- View User Statistics  
- Payment Processing  
- Role-Based Access  
- Promotion & Advertisement Management  

(Reference: Functionalities list) :contentReference[oaicite:6]{index=6}

---

## 📘 Academic Context

- **Course:** CA608 – Object Oriented System Analysis and Design  
- **Semester:** 5  
- **Project Type:** UML Case Study Project  
- **Deliverables:** Use Case, Activity, Class, and Sequence Diagrams  
- **Skills Learned:**  
  - UML Modeling  
  - System Requirements Analysis  
  - Actor Identification  
  - Workflow & Behavior Modeling  
  - Class Structure Design  
  - System Architecture Thinking  

This project demonstrates my ability to design complete software systems using structured analysis and UML modeling tools.

---

## 📄 License

This project is provided for academic and learning purposes.

