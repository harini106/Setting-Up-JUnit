Exercise 1: Setting Up JUnit
Objective
Set up JUnit in a Java project to begin writing unit tests.
Steps Performed
1. Created a Java Project
Opened IntelliJ IDEA/Eclipse.
Created a new Java (or Maven) project.
2. Added JUnit Dependency
Added the following dependency to the pom.xml file:
<dependency>
    <groupId>junit</groupId>
    <artifactId>junit</artifactId>
    <version>4.13.2</version>
    <scope>test</scope>
</dependency>

3. Created a Test Class
Created a test class named CalculatorTest.java:
import org.junit.Test;

public class CalculatorTest {

    @Test
    public void testExample() {
        System.out.println("JUnit is working successfully!");
    }
}

Expected Result
The project is successfully configured with JUnit, and the test class executes without errors.
