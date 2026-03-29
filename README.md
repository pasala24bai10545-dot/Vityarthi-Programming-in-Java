
# 🎓 Campus Course & Records Manager (CCRM)



## 📌 Project Overview

The **Campus Course & Records Manager (CCRM)** is a comprehensive **console-based Java SE application** designed to manage academic records for educational institutions.

It demonstrates **advanced Java programming concepts**, professional architecture, and real-world academic management features including students, courses, enrollments, and transcripts.

---

## 🚀 Key Features

* 📚 **Academic Management**

  * Full CRUD operations for students, courses, and enrollments

* 📊 **Grade Management**

  * GPA calculation
  * Transcript generation
  * Grade recording system

* 📁 **File Operations**

  * CSV import/export
  * Automated backup system

* ⚙️ **Advanced Java Concepts**

  * OOP, Streams, Lambdas, Design Patterns

* 🏢 **Professional Quality**

  * Enterprise-level structure
  * Clean architecture & documentation

---

## ⚡ Quick Start

### 🔧 Prerequisites

* Java **17+**
* Command line (Windows/Linux/macOS)
* Git

---

### 🛠️ Installation & Setup

```bash
git clone https://github.com/CodeWithAmrat/CCRM.git
cd CCRM
```

---

### ✅ Verify Java Installation

```bash
java -version
javac -version
```

> Should display Java 17 or higher

---

### ⚙️ Compile the Project

**Windows**

```bash
scripts\compile.bat
```

**Linux/macOS**

```bash
chmod +x scripts/compile.sh
./scripts/compile.sh
```

---

### ▶️ Run the Application

**Windows**

```bash
scripts\run.bat
```

**Linux/macOS**

```bash
./scripts/run.sh
```

---

## 🎮 First Run Demo

### 📥 Import Sample Data

1. Choose **Option 4 (Import/Export Data)**
2. Select:

   * Option 1 → Import Students
   * Option 2 → Import Courses

---

### 🔍 Explore Features

* Option 1 → View Students
* Option 2 → View Courses
* Option 3 → Enrollment Demo
* Option 7 → Advanced Features Demo

---

### 💾 Export & Backup

* Option 4 → 3 → Export Data
* Option 5 → Create Backup

---

## 📂 Project Structure

```
CCRM/
├── src/edu/ccrm/
│   ├── cli/                # CLI entry point
│   ├── config/             # App configuration (Singleton)
│   ├── domain/             # Core entities
│   ├── enums/              # Enums (Semester, Grade)
│   ├── exceptions/         # Custom exceptions
│   ├── interfaces/         # Interfaces
│   ├── io/                 # File handling
│   ├── service/            # Business logic
│   ├── store/              # Data persistence
│   └── util/               # Utilities
├── test-data/              # Sample CSV files
├── scripts/                # Compile & run scripts
├── exports/                # Output data
├── backups/                # Backup files
├── screenshots/            # UI images
├── video/                  # Demo videos
├── README.md
├── USAGE.md
├── DEMO_SCRIPT.md
└── IMPLEMENTATION_SUMMARY.md
```

---

## 🎯 Java Concepts Demonstrated

### 🧠 Object-Oriented Programming

* Encapsulation
* Inheritance (`Person → Student/Instructor`)
* Abstraction
* Polymorphism

---

### ⚡ Advanced Features

* Enums with fields & constructors
* Interfaces with default methods
* Generics
* Streams API
* Lambdas & Method References

---

### 🏗️ Design Patterns

* Singleton → `AppConfig`, `DataStore`
* Builder → `Course`
* Strategy Pattern

---

### 🔄 Control Structures

* Enhanced Switch
* All loop types
* Conditional logic
* Jump statements

---

### 💾 Memory Management

* Try-with-resources
* Immutable classes
* Defensive copying

---

### ⚠️ Exception Handling

* Custom exceptions
* Multi-catch blocks
* Assertions

---

### 📁 File I/O (NIO.2)

* Path API
* Files utility
* Stream processing
* Recursive directory traversal

---

### 🧩 Advanced Concepts

* Anonymous inner classes
* Nested classes
* Type casting (up/down)
* Method overloading
* Arrays utilities

---

## 📋 Usage Guide

### 👨‍🎓 Student Management

* Add / Update / Delete students
* Search students
* View profiles & history

---

### 📚 Course Management

* Manage course catalog
* Filter courses
* Assign instructors

---

### 📝 Enrollment System

* Enroll students
* Validate credit limits
* Prevent duplicates

---

### 📊 Grade Management

* Record grades
* Calculate GPA
* Generate transcripts

---

### 📂 File Operations

* Import CSV
* Export data
* Create backups

---

## 🎯 Advanced Features Demo

Select **Option 7** to explore:

* Control structures
* Arrays utilities
* Type casting
* Inner classes
* Immutable objects

---

## 🏗️ Technical Architecture

### 📦 Domain Layer

* `Person` (Abstract)
* `Student`, `Instructor`
* `Course`, `Enrollment`
* `Transcript`

---

### ⚙️ Service Layer

* StudentService
* CourseService
* EnrollmentService
* ReportService
* TranscriptService

---

### 🏢 Infrastructure Layer

* DataStore (Singleton)
* FileIO
* BackupUtil
* AppConfig

---

## 📜 Business Logic

### 📌 Enrollment Rules

* Max credits per semester
* No duplicate enrollment
* Student status validation
* Course availability

---

### 📊 Grade System

* Letter → Points conversion
* GPA calculation
* Transcript generation

---

## 📄 Data Formats

### 👨‍🎓 Students CSV

```
id,regNo,fullName,email,status
S1,REG1001,Alice Johnson,alice@example.com,ACTIVE
S2,REG1002,Bob Smith,bob@example.com,ACTIVE
```

---

### 📚 Courses CSV

```
code,title,credits,instructor,semester,department
CS101,Intro to CS,4,Dr. Ada,FALL,CSE
MA101,Calculus I,4,Dr. Euler,SPRING,MAT
```

---

## 🛠️ Development Setup

### 💻 IDE Configuration

#### Eclipse

1. Create Java project
2. Set `src/` as source
3. Configure build path
4. Run `Main.java`

#### IntelliJ IDEA

1. Open project
2. Set SDK to Java 17+
3. Mark `src` as sources root
4. Run `Main.java`

#### VS Code

1. Install Java Extension Pack
2. Open project
3. Configure runtime
4. Run `Main.java`

---

## ⚙️ Build Configuration

* No external dependencies
* Uses simple scripts:

```bash
# Windows
scripts\compile.bat

# Linux/macOS
scripts/compile.sh
```

---

## 📚 Documentation

* `USAGE.md` → Detailed guide
* `DEMO_SCRIPT.md` → Demo script
* `IMPLEMENTATION_SUMMARY.md` → Technical details
* JavaDocs → Inline code documentation

---

## 🤝 Contributing

1. Fork the repo
2. Create feature branch
3. Make changes
4. Add tests
5. Submit PR

---

## 👤 Author

**Charishma**

* GitHub: https://github.com/pasala24bai10545-dot
* Project: Campus Course & Records Manager

---


