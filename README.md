API-Serialization-Deserialization-Framework-Java

A compact learning and practice repository demonstrating how to use Jackson, POJO Models, and Rest Assured together for API Automation.
It includes end-to-end examples of serialization, deserialization, nested JSON handling, JSON → POJO conversion, and POJO → JSON payload creation.

📌 Project Overview

This project is divided into three major sections:

1️⃣ Jackson Annotation Examples (src/main/java/JacksonAnnotationExample/)

Covers:

@JsonIgnore

@JsonIgnoreProperties

@JsonProperty

Serialization & Deserialization examples

Working with full data models (Book, Employee, Staff, Members, etc.)

2️⃣ POJO Classes (src/main/java/PojoClasses/)

Contains simple and nested POJO models such as:

Book

Employee

Members

Person

Staff

Nested POJO combinations

These models are used across all test examples.

3️⃣ Test Automation (src/test/java/)
✔ PoJoExamples

Real API automation practice using:

Creating JSON payloads using POJO

Nested object creation

Array to POJO conversion

API call examples with Rest Assured

Retry mechanism

Dummy APIs for learning JSON → POJO mapping

✔ JsonToPojo

Examples showing:

Convert JSON file → POJO

Update JSON without POJO

Read and update JSON properties

✔ Payloads

Stores JSON files used in tests
(e.g., address.json)

🚀 Tech Stack

Java

Rest Assured

Jackson Databind

TestNG

Maven

🔧 Features Implemented

JSON Serialization / Deserialization

Jackson Annotations (Ignore, Property Mapping, etc.)

POJO-Based Payload Creation

Nested & Array JSON Handling

JSON Schema Handling (extendable)

Reusable Payload Classes

API Request/Response Mapping with POJO

📂 Project Structure Snapshot
src
 ├── main
 │    └── java
 │         ├── JacksonAnnotationExample
 │         └── PojoClasses
 │
 └── test
      └── java
           ├── PoJoExamples
           ├── JsonToPojo
           └── Payloads

👨‍💻 Author

Arpit Choubey — SDET | QA | Automation Engineer
🔗 LinkedIn | Medium

⭐ Support

If this repository helped you, please Star ⭐ the repo!
