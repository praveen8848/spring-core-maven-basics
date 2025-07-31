Spring Dependency Injection Example – XML Configuration
This is a simple Spring Core project using XML-based configuration to demonstrate Dependency Injection and basic Spring container usage.

✅ Spring Core Concepts
ApplicationContext – Spring's container for managing beans.

XML Configuration (spring.xml) – Used to define beans and their dependencies.

Beans and Interfaces – You created Doctor and Staff as part of a modular design.

Dependency Injection via Constructor – Injected values (like qualification) into the bean.

✅ Spring Project Setup
Maven project with dependencies for:

spring-core

spring-context

spring-beans

Configured Java 21 in pom.xml.

📁 Project Structure
bash
Copy
Edit
Maven_Project/
├── src/main/java/org/example/
│   ├── Main.java              # Loads Spring context and calls methods
│   ├── Doctor.java            # A Spring-managed bean
│   ├── Staff.java             # (Assumed) interface for Doctor and others
│   └── Nurse.java             # (Optional) another bean
├── src/main/resources/
│   └── spring.xml             # Spring bean configuration
├── pom.xml                    # Maven dependencies
