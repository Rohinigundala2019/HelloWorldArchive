# Java Hello World

## 1. How to Install
### All Platforms:
1. Download **JDK 17+** from [Oracle](https://www.oracle.com/java/technologies/downloads/).
2. Add Java to your system `PATH`.

Verify installation:
```bash
javac -version  # Should show JDK 17+
java -version
```

---

## 2. How to Run
1. **Compile** (creates `HelloWorld.class`):
   ```bash
   javac HelloWorld.java
   ```
2. **Execute** (no `.class` extension):
   ```bash
   java HelloWorld
   ```

---

## 3. Output
```
Hello, World!
```

---

### Notes:
- The class name (`HelloWorld`) must match the filename exactly.
- Requires JDK 11 or higher (tested with OpenJDK 17).
