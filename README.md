
# 🚀 API Serialization & Deserialization Framework | Java | REST Assured | Jackson | TestNG

<p align="center">

![Java](https://img.shields.io/badge/Java-REST%20Assured-red?style=for-the-badge&logo=openjdk)
![Jackson](https://img.shields.io/badge/Jackson-JSON-blue?style=for-the-badge)
![REST API](https://img.shields.io/badge/REST-API%20Testing-success?style=for-the-badge)
![TestNG](https://img.shields.io/badge/TestNG-Automation-red?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-Build-orange?style=for-the-badge&logo=apachemaven)
![GitHub](https://img.shields.io/badge/Open-Source-181717?style=for-the-badge&logo=github&logoColor=white)

</p>

---

# 📌 Project Overview

Modern REST APIs exchange data in **JSON**, making **Serialization** and **Deserialization** essential skills for every **QA Automation Engineer**, **SDET**, and **API Test Engineer**.

This repository demonstrates how to build clean, maintainable, and scalable API automation using **Java**, **Jackson**, **POJO Models**, and **REST Assured**. It covers real-world serialization/deserialization techniques, nested JSON objects, Jackson annotations, reusable payload models, and response mapping used in enterprise automation frameworks.

Whether you're preparing for interviews or building production-grade API tests, this project provides practical examples of converting Java objects to JSON and JSON responses back into Java objects.

---

# 🎯 Repository Objectives

This project demonstrates how to:

- Build reusable POJO models for API automation
- Serialize Java Objects into JSON payloads
- Deserialize JSON responses into Java Objects
- Handle nested JSON structures
- Work with arrays and collections
- Use Jackson annotations effectively
- Perform API testing using REST Assured
- Create maintainable API automation frameworks

---

# 🚀 Key Features

✅ JSON Serialization

✅ JSON Deserialization

✅ Jackson Databind

✅ Jackson Annotations

✅ Nested POJO Objects

✅ REST Assured Integration

✅ Request Payload Creation

✅ Response Mapping

✅ JSON File Handling

✅ Modular Project Structure

✅ Real API Examples

---

# 🏗 Project Structure

```text
API-Serialization-Deserialization-Framework-Java
│
├── src
│
├── main
│   │
│   └── java
│       │
│       ├── JacksonAnnotationExample
│       │
│       └── PojoClasses
│
├── test
│   │
│   └── java
│       │
│       ├── PoJoExamples
│       │
│       ├── JsonToPojo
│       │
│       └── Payloads
│
├── pom.xml
│
└── README.md
```

---

# 📚 Repository Modules

## 1️⃣ Jackson Annotation Examples

Location

```
src/main/java/JacksonAnnotationExample/
```

Examples included:

- @JsonIgnore
- @JsonIgnoreProperties
- @JsonProperty
- Serialization
- Deserialization

These examples demonstrate how Jackson customizes JSON serialization and deserialization in enterprise applications.

---

## 2️⃣ POJO Models

Location

```
src/main/java/PojoClasses/
```

Contains reusable Java models including:

- Book
- Employee
- Staff
- Members
- Person
- Nested Objects

These POJO classes are used throughout the API automation examples.

---

## 3️⃣ REST Assured API Examples

Location

```
src/test/java/
```

Includes practical automation scenarios such as:

✔ Creating JSON Payloads

✔ Nested Objects

✔ Object Serialization

✔ Response Deserialization

✔ Array Handling

✔ Retry Mechanism

✔ Dummy REST APIs

---

## 4️⃣ JSON to POJO

Examples include:

- JSON File → Java Object
- Java Object → JSON
- Updating JSON Files
- Reading JSON Properties

---

## 5️⃣ Payload Repository

Reusable JSON payloads stored separately for cleaner automation.

Example:

```
Payloads/

address.json

employee.json

book.json
```

---

# 🔄 Serialization Workflow

```
Java Object (POJO)

        │

        ▼

Jackson ObjectMapper

        │

        ▼

JSON Request Body

        │

        ▼

REST Assured API Request
```

---

# 🔄 Deserialization Workflow

```
REST API Response

        │

        ▼

JSON Response

        │

        ▼

Jackson ObjectMapper

        │

        ▼

Java Object (POJO)
```

---

# 🛠 Technologies Used

| Category | Technology |
|----------|------------|
| Language | Java |
| API Automation | REST Assured |
| JSON Library | Jackson Databind |
| Framework | TestNG |
| Build Tool | Maven |
| Version Control | Git |
| Repository | GitHub |

---

# 💼 Skills Demonstrated

This repository showcases expertise in:

- REST API Testing
- Java
- REST Assured
- Jackson Databind
- Serialization
- Deserialization
- POJO Modeling
- Nested JSON
- JSON Arrays
- Object Mapping
- API Payload Design
- JSON File Handling
- Test Automation Framework Design

---

# ▶️ Getting Started

## Clone Repository

```bash
git clone https://github.com/ArpitChoubey/API-Serialization-Deserialization-Framework-Java.git
```

---

## Install Dependencies

```bash
mvn clean install
```

---

## Execute Tests

```bash
mvn test
```

or execute using TestNG from your IDE.

---

# 🎯 Learning Outcomes

After completing this repository, you will understand:

- Java Object Mapping
- Jackson Serialization
- Jackson Deserialization
- POJO Modeling
- Nested Objects
- REST Assured Payload Creation
- Response Mapping
- Enterprise API Automation Practices

---

# 💡 Why Serialization Matters

Serialization and Deserialization are fundamental concepts used in almost every enterprise API automation framework.

Mastering these concepts enables you to:

- Build reusable frameworks
- Reduce hardcoded JSON
- Improve code maintainability
- Simplify request payload creation
- Improve response validation

These are core skills expected from modern **SDETs**, **QA Automation Engineers**, and **Backend API Testers**.

---

# 💼 Ideal For

This repository is valuable for:

- QA Automation Engineers
- API Automation Engineers
- SDETs
- Java Developers
- Manual Testers transitioning to Automation
- Students preparing for Automation Interviews

---



# 👨‍💻 About the Author

## Arpit Choubey

**SDET | QA Automation Engineer | Java | REST Assured | Selenium | Playwright | Appium | TestNG | Maven | SQL | Jenkins**

Passionate about building scalable automation frameworks, learning modern testing technologies, and contributing practical open-source projects for the QA community.

---

# 🌐 Connect With Me

### GitHub

https://github.com/ArpitChoubey

### LinkedIn

https://www.linkedin.com/in/arpitchoubey/

### Medium

https://medium.com/@ArpitChoubey9

---

# ⭐ Support

If this repository helped you learn API Serialization & Deserialization, please consider giving it a **Star ⭐**.

Your support motivates me to continue building high-quality open-source projects for the QA Automation community.

---

## 💡 *"Clean API automation starts with clean object models. Master Serialization, Deserialization, and POJOs to build scalable automation frameworks."*
