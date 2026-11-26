# Apache Maven – Hands-on Practice 🚀

## 📌 Overview

This repository documents my hands-on learning and exploration of **Apache Maven**, a build automation and dependency management tool widely used in Java projects.

The objective of this practice was to understand how Java applications are compiled, tested, and packaged using Maven, along with learning how project configurations, dependencies, and plugins are managed through the `pom.xml` file.

## 🎯 Learning Objectives

- Understand Apache Maven and its purpose.
- Explore the `pom.xml` (Project Object Model) file.
- Understand dependencies and Maven plugins.
- Learn the Maven Build Lifecycle.
- Practise commonly used Maven commands.
- Understand WAR packaging for Java web applications.
- Troubleshoot Java heap space errors during builds.

## 🛠️ Technologies & Tools

- Apache Maven
- Java
- Linux (Ubuntu)
- XML
- JVM
- WAR Packaging

## 📚 Concepts Covered

### 1. Introduction to Apache Maven

Apache Maven is a build automation and project management tool primarily used for Java applications.

It helps automate:
- Source code compilation.
- Dependency management.
- Unit testing.
- Application packaging.
- Build processes.

### 2. Understanding pom.xml

The `pom.xml` (Project Object Model) is the central configuration file of a Maven project.

It defines:
- Group ID
- Artifact ID
- Project version
- Dependencies
- Build plugins
- Packaging configuration

### 3. Dependencies and Plugins

**Dependencies:** External libraries required by a Java application.

**Plugins:** Components that extend Maven functionality and perform tasks such as compiling, testing, and packaging applications.

### 4. Maven Build Lifecycle

Explored the important phases of the Maven build lifecycle.

| Phase | Description |
|---|---|
| validate | Validates project configuration |
| compile | Compiles source code |
| test | Executes unit tests |
| package | Packages the application |
| verify | Performs verification checks |
| install | Installs the package into the local repository |
| deploy | Deploys the package to a remote repository |

## 💻 Maven Commands Practised

| Command | Description |
|---|---|
| `mvn clean` | Removes previously generated build files |
| `mvn compile` | Compiles the source code |
| `mvn test` | Executes unit tests |
| `mvn package` | Packages the application |
| `mvn clean package` | Cleans and packages the application |

## 📦 WAR Packaging

Worked with a Java web application and explored WAR (Web Application Archive) packaging.

A WAR file packages Java web application resources, classes, and dependencies for deployment to compatible servlet containers such as Apache Tomcat.

## ⚠️ Challenge Faced: Java Heap Space Error

During WAR packaging, I encountered a **Java heap space error**.

This helped me understand:

- Maven build processes run on the JVM.
- JVM heap memory is used during build execution.
- Insufficient heap allocation can cause build failures.
- Memory troubleshooting is important when working with build automation tools.

## 💡 Key Takeaways

- Understood Apache Maven and its role in Java development.
- Learned the structure and purpose of `pom.xml`.
- Explored dependencies and Maven plugins.
- Practised Maven build lifecycle commands.
- Understood WAR packaging.
- Gained practical exposure to JVM memory troubleshooting.

## 🚀 What's Next?

Explore Maven integration with Jenkins and understand how automated Java builds, testing, and packaging fit into CI/CD pipelines.

---

**Learning by doing. Building practical knowledge one tool at a time.**# maven-build
Build Process and Build Tools 
