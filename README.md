# Contacts_App

## Overview
Contacts_App is a Windows Forms (WinForms) desktop application built to practice ADO.NET CRUD (Create, Read, Update, Delete) operations on a Contacts database. The project is organized using a **3-tier architecture** to separate concerns clearly and ensure maintainability.

---

## Features
- Add new contacts
- View and list all contacts
- Update existing contact information
- Delete contacts
- Utilizes ADO.NET for database connectivity and operations
- Implements 3-tier design:
  - Presentation Layer (WinForms UI)
  - Business Logic Layer (BLL)
  - Data Access Layer (DAL)

---

## Architecture
### 3-Tier Design

1. **Presentation Layer (WinForms UI)**  
   User interface built with Windows Forms to interact with users.

2. **Business Logic Layer (BLL)**  
   Contains validation and business rules, acting as an intermediary between UI and data.

3. **Data Access Layer (DAL)**  
   Directly handles database interactions using ADO.NET with SQL commands and connections.

---

## Technologies Used
- C# with WinForms
- ADO.NET
- Microsoft SQL Server 
- Visual Studio

---

## Setup Instructions

### Prerequisites
- SQL Server instance installed and running
- Visual Studio with .NET desktop development workload

