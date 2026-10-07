# Intelligent Organ Donation Management System

## Object Oriented Techniques and Systems (OOTS)

**A Capstone Project for Managing Organ Donation, Donor–Recipient Matching and Transplant Records**

---

## 1. Project Overview

The **Intelligent Organ Donation Management System** is a software-based capstone project developed as part of the **Object Oriented Techniques and Systems (OOTS)** course.

The main purpose of this project is to design an organized system for managing the different entities and activities involved in the organ donation and transplantation process.

Organ donation involves multiple entities such as:

- Donors
- Recipients
- Organs
- Hospitals
- Transplant Coordinators
- System Users
- Matching Results
- Transplant Records

In a real-world environment, these entities are interconnected and require proper management of information and relationships.

This project models these real-world entities as **classes and objects** and applies important Object-Oriented concepts such as:

- Encapsulation
- Abstraction
- Inheritance
- Polymorphism
- Association
- Aggregation
- Composition
- Exception Handling

The system also includes the concept of a **donor–recipient matching module**, which is intended to provide structured and traceable decision-support information for potential matches.

---

# 2. Problem Statement

Organ donation and transplantation involve several stakeholders, processes and records.

The major challenge is to maintain donor, recipient, organ, hospital and transplant information in a structured manner while also supporting the identification of suitable donor–recipient combinations.

The system needs to address problems such as:

- Maintaining donor information
- Maintaining recipient information
- Managing available organ information
- Representing relationships between different entities
- Handling different user responsibilities
- Validating incomplete or incorrect records
- Supporting donor–recipient compatibility matching
- Maintaining transplant records
- Protecting sensitive donor and recipient information
- Making matching-related information explainable and traceable

The **Intelligent Organ Donation Management System** proposes an object-oriented approach to organize these activities into separate but interconnected modules.

---

# 3. Project Objectives

The major objectives of the project are:

### 3.1 Donor Management
To maintain structured information about donors and their donation-related details.

### 3.2 Recipient Management
To maintain recipient information and waiting-list related details.

### 3.3 Organ Management
To represent available organs and maintain their relevant information.

### 3.4 Donor–Recipient Matching
To develop a compatibility-based matching component that can identify potential donor–recipient pairs.

### 3.5 Hospital Management
To represent hospitals and their involvement in organ and transplant management.

### 3.6 Transplant Record Management
To maintain structured records related to transplant activities.

### 3.7 Object-Oriented Design
To apply OOTS concepts to a real-world healthcare-related problem.

### 3.8 Data Protection
To use encapsulation and controlled access for sensitive donor and recipient information.

### 3.9 Validation and Exception Handling
To handle missing, invalid, incomplete and incompatible information safely.

### 3.10 Traceable Decision Support
To make matching-related results structured, reviewable and traceable.

---

# 4. Target Users and Stakeholders

The proposed system involves different stakeholders, each having different responsibilities.

| Stakeholder | Responsibility |
|---|---|
| **Donor** | Provides donation information and consent |
| **Recipient** | Maintains waiting-list and medical information |
| **Transplant Coordinator** | Reviews potential matches and coordinates allocation |
| **Hospital / Medical Team** | Manages organ and transplant-related information |
| **System Administrator** | Manages users, access and system records |
| **Development Team** | Designs, develops, tests and maintains the system |

---

# 5. Proposed Solution

The proposed solution is an **Object-Oriented Organ Donation Management System** in which each major real-world entity is represented using a separate class.

The system is structured around the following major entities:

```text
User
 |
 +-------------------+
 |                   |
Donor             Recipient
 |                   |
 |                   |
Organ           MatchResult
 |                   |
 +---------+---------+
           |
        Hospital
           |
    TransplantRecord
