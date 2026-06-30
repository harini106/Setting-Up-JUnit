# Exercise 1: Setting Up JUnit

## Overview

This project demonstrates how to set up **JUnit 4** in a Java project and create a simple unit test. It provides the basic configuration required to start writing and executing unit tests.

---

## Project Structure

```text
JUnit_Setup/
│── pom.xml
│── src/
│   ├── main/java/
│   └── test/java/
│       └── CalculatorTest.java
└── README.md
```

---

## Objective

Set up JUnit in a Java project and verify the configuration by creating a simple test class.

---

## Steps Performed

### 1. Create a Java Project

Create a new Java or Maven project using IntelliJ IDEA or Eclipse.

### 2. Add JUnit Dependency

Add the following dependency to the `pom.xml` file.

```xml
<dependency>
    <groupId>junit</groupId>
    <artifactId>junit</artifactId>
    <version>4.13.2</version>
    <scope>test</scope>
</dependency>
```

### 3. Create a Test Class

Create a new test class named `CalculatorTest.java`.

```java
import org.junit.Test;

public class CalculatorTest {

    @Test
    public void testExample() {
        System.out.println("JUnit is working successfully!");
    }
}
```

---

## Prerequisites

- Java Development Kit (JDK)
- IntelliJ IDEA or Eclipse
- Maven
- JUnit 4.13.2

---

## How to Run

Run the test class from your IDE.

**Eclipse:**
- Right-click `CalculatorTest.java`
- Select **Run As → JUnit Test**

**IntelliJ IDEA:**
- Right-click `CalculatorTest.java`
- Select **Run 'CalculatorTest'**

---

## Expected Output

The JUnit test executes successfully without any errors, confirming that JUnit has been configured correctly.

---

## Learning Outcomes

After completing this exercise, you will be able to:

- Set up JUnit in a Java project.
- Add JUnit dependencies using Maven.
- Create a basic unit test.
- Execute JUnit test cases.
- Verify the JUnit setup successfully.

---

## Author

**Harini**
