# Contributing Guide 🌟

Welcome! We’re excited you want to contribute to this collection of "Hello World" programs.  
Follow these guidelines to ensure your contribution aligns with the project’s structure.

---

## Table of Contents
- [Prerequisites](#prerequisites)
- [Adding a New Language](#adding-a-new-language)
- [Improving Existing Code](#improving-existing-code)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Code of Conduct](#code-of-conduct)

---

## Prerequisites
- Basic familiarity with Git and GitHub.
- Ensure the code you submit **runs successfully** on your local machine.

---

## Adding a New Language
### 1. Folder Structure
- Create a **new folder** under `languages/` named after the language (e.g., `languages/kotlin`).  
- Use **lowercase** for folder names (e.g., `csharp`, not `CSharp`).

### 2. Code File
- Name the file descriptively (e.g., `hello.kt`, `hello_v2.py` for version-specific examples).  
- Include **code comments** at the top specifying:
  ```kotlin
  // Language: Kotlin (1.9.0+)
  // Run: kotlinc hello.kt -include-runtime -d hello.jar && java -jar hello.jar
  ```

### 3. Language-Specific README
Create a `README.md` in the language folder using this template:
```markdown
# [Language Name] Hello World

## 1. How to Install  
[Steps to install the compiler/runtime]

## 2. How to Run  
[Commands to compile/execute the code]

## 3. Output  
```
Hello, World!
```

[Optional: Add version requirements or troubleshooting tips]
```

### 4. Update the Main README
Add your language to the table in the root [`README.md`](README.md) following this format:
```markdown
| Python      | `hello_v3.py` | 3.10+ | `python hello_v3.py` |
```

---

## Improving Existing Code
- **Version-specific examples**: Add new files (e.g., `hello_v2.py` for Python 2.x).  
- **Better comments**: Clarify build/run steps or version requirements.  
- **Fix errors**: Test changes locally before submitting.

---

## Pull Request Guidelines
1. **Reference an issue**: If your PR addresses an open issue, mention it (e.g., `Closes #12`).  
2. **Keep it focused**: One PR per language or improvement.  
3. **Provide context**: Explain why your contribution matters.  

---


## License
By contributing, you agree to license your work under the [MIT License](LICENSE).

---

**Thank you for making this project awesome!** 🚀