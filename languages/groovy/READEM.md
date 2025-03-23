# Groovy

- Groovy is a powerful, dynamic programming language for the Java Virtual Machine (JVM) that combines Python-like simplicity with Java's robustness. 
- It seamlessly integrates with Java, allowing developers to leverage existing Java libraries while offering concise syntax, scripting capabilities, and advanced features like closures and metaprogramming. 
- Groovy is widely used for scripting, testing, and building applications, making it a versatile choice for developers.

## Getting Started

### 1. Install:
- Groovy runs on the Java Virtual Machine (JVM), so you need to have Java installed.
- Download [JDK](https://www.oracle.com/java/technologies/downloads/?er=221886).
- Set the *_JAVA_HOME_* environment variable:
    - Open Settings > System > About > Advanced system settings > Environment Variables.
    - Under _System_ variables, click New and add:
        - Variable name: *_JAVA_HOME_*
        - Variable value: Path to your JDK installation (e.g., C:\Program Files\Java\jdk-21).
    - Edit the _Path_ variable and add *_%JAVA_HOME%\bin_*.
- Verify JAVA installation:
```bash
java -version
```
- Download the latest Groovy binary from [Groovy](https://groovy.apache.org/download.html).
- Extract the downloaded ZIP file to a directory, e.g., C:\groovy.
- Set the *_GROOVY_HOME_* environment variable:
    - Open Environment Variables as described above.
    - Add a new _System_ variable:
        - Variable name: *_GROOVY_HOME_*
        - Variable value: Path to your Groovy installation (e.g., C:\groovy\groovy-4.0.0).
    - Edit the _Path_ variable and add *_%GROOVY_HOME%\bin_*.
- Verify Groovy installation:
```bash
groovy -version
```

---

### 2. Execute:
```bash
groovy HelloWorld.groovy
```

---

### 3. Output:
```bash
Hello World...!!!
```