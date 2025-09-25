# Campus Course & Records Manager (CCRM)

A comprehensive console-based Java application for managing academic records, courses, students, and grades in educational institutions.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technical Requirements](#technical-requirements)
- [Installation & Setup](#installation--setup)
- [How to Run](#how-to-run)
- [Java Platform Information](#java-platform-information)
- [Project Structure](#project-structure)
- [Syllabus Topic Mapping](#syllabus-topic-mapping)
- [Usage Guide](#usage-guide)
- [Sample Data](#sample-data)
- [Enabling Assertions](#enabling-assertions)

## 🎯 Project Overview

CCRM is a Java SE application that provides comprehensive management of:
- Student records and profiles
- Course catalog and details
- Student enrollments and course registration
- Grade recording and transcript generation
- Data import/export and backup operations

## ✨ Features

### Student Management
- Add, update, list, and deactivate students
- Student profiles with complete academic information
- Search functionality using various criteria

### Course Management
- Create and maintain course catalog
- Assign instructors to courses
- Filter and search courses by department, semester, or instructor

### Enrollment System
- Enroll/unenroll students from courses
- Credit limit validation (max 24 credits per semester)
- Semester-based enrollment tracking

### Grading System
- Record marks and calculate letter grades
- GPA computation and transcript generation
- Grade distribution reports

### File Operations
- Import/export data in CSV format
- Automated backup with timestamping
- Recursive directory size calculation

### Reporting
- GPA distribution analysis
- Top student identification
- Comprehensive academic reports

## 💻 Technical Requirements

- **Java Version**: JDK 8 or higher
- **Platform**: Java Standard Edition (SE)
- **Storage**: Local file system for data persistence
- **Interface**: Console-based menu system

## 🔧 Installation & Setup

### Windows JDK Installation Steps

1. **Download JDK**
    - Visit [Oracle JDK Downloads](https://www.oracle.com/java/technologies/downloads/)
    - Download appropriate JDK version for Windows

2. **Install JDK**
    - Run the installer executable
    - Follow installation wizard steps
    - Accept license agreement
    - Choose installation directory (default recommended)

3. **Set Environment Variables**
    - Right-click on "This PC" → Properties → Advanced System Settings
    - Click "Environment Variables"
    - Create new system variable:
        - Variable name: `JAVA_HOME`
        - Variable value: `C:\Program Files\Java\jdk-21` (adjust version as needed)
    - Edit `Path` variable:
        - Add `%JAVA_HOME%\bin`

4. **Verify Installation**
    - Open Command Prompt
    - Run: `java -version`
    - Expected output: Java version information

![JDK Installation Verification](screenshots/java-version.png)

### Eclipse IDE Setup

1. **Download and Install Eclipse**
    - Download Eclipse IDE from [eclipse.org](https://www.eclipse.org/downloads/)
    - Run installer and select "Eclipse IDE for Java Developers"

2. **Create New Project**
    - Launch Eclipse
    - File → New → Java Project
    - Project name: `CCRM`
    - Use default JRE configuration

3. **Add Source File**
    - Right-click `src` folder → New → Class
    - Name: `CCRM`
    - Copy-paste the complete code from CCRM.java

4. **Run Configuration**
    - Right-click project → Run As → Java Application
    - Or use Ctrl+F11 shortcut

![Eclipse Project Setup](screenshots/eclipse-setup.png)

## 🚀 How to Run

### Method 1: Command Line
```bash
# Compile the application
javac CCRM.java

# Run the application
java CCRM

# Run with assertions enabled
java -ea CCRM

Got it 👍 You want a professional `README.md` file for your **CCRM** GitHub repo that follows the exact deliverables list from your assignment. I’ll draft a complete README for you, including placeholders where you’ll insert your screenshots, commands, and demo links.

Here’s a ready-to-use version ⬇️

---

# CCRM – Course & Curriculum Resource Manager

## 📌 Project Overview

CCRM (**Course & Curriculum Resource Manager**) is a Java-based system that helps manage courses, semesters, and related resources efficiently.
It demonstrates **Java programming fundamentals** with practical examples like file handling, OOP concepts, streams, predicates, and date/time APIs.

This repository includes:

* Source code (`.java` files) with a runnable **main class** (`CCRM.java`)
* Documentation (`README.md`, `USAGE.md`)
* Screenshots (JDK setup, Eclipse project, program run)
* Sample test data (`/test-data/*.csv`)

---

## 🚀 How to Run

### Requirements

* **JDK Version:** Java SE 17+ (tested with JDK 17.0.10)
* **IDE (Optional):** Eclipse 2023-09 or newer

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/BLUEhorizon28/CCRM.git
   cd CCRM
   ```
2. Compile the program:

   ```bash
   javac src/CCRM.java
   ```
3. Run the main class:

   ```bash
   java -cp src CCRM
   ```

### Running via Eclipse

1. Open Eclipse → File → Import → Existing Projects.
2. Select the `CCRM` folder.
3. Right-click `CCRM.java` → Run As → Java Application.

---

## 📖 Evolution of Java (Short Bullets)

* **1995:** Java 1.0 released by Sun Microsystems.
* **1998:** Java 2 (J2SE, J2EE, J2ME) introduced.
* **2004 (Java 5):** Generics, enhanced for-loops, metadata.
* **2014 (Java 8):** Streams, Lambdas, Date/Time API.
* **2017 (Java 9):** Modular system (Project Jigsaw).
* **2021+:** Regular 6-month release cycle, latest features like records, sealed classes, pattern matching.

---

## 🖥 Java ME vs SE vs EE

| Feature         | Java ME (Micro Edition)  | Java SE (Standard Edition) | Java EE (Enterprise Edition)              |
| --------------- | ------------------------ | -------------------------- | ----------------------------------------- |
| Target Platform | Mobile, embedded devices | Desktop & standalone apps  | Web, distributed, enterprise apps         |
| Libraries       | Limited, lightweight     | Core libraries, full API   | SE + enterprise APIs (JPA, Servlets, EJB) |
| Use Cases       | IoT, feature phones      | General apps, tools, games | Banking, e-commerce, large systems        |

---

## ⚙️ JDK, JRE, JVM Explained

* **JVM (Java Virtual Machine):** Runs Java bytecode, platform-independent.
* **JRE (Java Runtime Environment):** JVM + libraries for running Java programs.
* **JDK (Java Development Kit):** JRE + compiler & tools (javac, javadoc, etc.) for developing Java programs.

---

## 🪟 Windows Installation & Eclipse Setup

### JDK Installation (Windows)

1. Download JDK 17 from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Install and set **JAVA_HOME** in Environment Variables.
3. Verify installation:

   ```bash
   java -version
   ```

✅ *Screenshot here →* `screenshots/jdk_installation.png`

### Eclipse Setup

1. Download Eclipse IDE.
2. Configure workspace → Import project.
3. Verify by running `CCRM.java`.

✅ *Screenshot here →* `screenshots/eclipse_setup.png`

---

## 📑 Mapping Table (Syllabus → Code Reference)

| Syllabus Topic       | File/Class/Method          |
| -------------------- | -------------------------- |
| OOP (Classes, Enums) | `CCRM.java`, `Domain.java` |
| File Handling        | `BackupManager.java`       |
| Streams & Predicates | `CourseManager.java`       |
| Date & Time API      | `Semester.java`            |
| Exception Handling   | `ErrorHandler.java`        |
| Assertions           | `CCRM.java (main)`         |

---

## 🛠️ Assertions in Java

### Enabling Assertions

Run program with `-ea` flag:

```bash
java -ea -cp src CCRM
```

### Example Command

```java
assert course != null : "Course must not be null";
```

---

## 📂 Repository Structure

```
CCRM/
│── src/                 # Source code (Java files)
│── test-data/           # Sample CSVs for import/export
│── screenshots/         # Setup, run, verification screenshots
│── exports/             # Program backups/exports
│── README.md            # Documentation
│── USAGE.md             # Sample commands and usage guide
```

---

## ▶️ Demo Video (Optional)

📹 [Watch Demo](https://youtu.be/your-demo-link)

---

## 🙌 Acknowledgements

* Oracle Java Documentation
* Eclipse IDE documentation
* [Baeldung Java Tutorials](https://www.baeldung.com/)


