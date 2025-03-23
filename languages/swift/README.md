# Swift

- Swift is a powerful and intuitive programming language developed by Apple for building apps for iOS, macOS, watchOS, and beyond. 
- It is designed to be safe, fast, and expressive, making it a great choice for both beginners and experienced developers.

## Hello World:
### 1. Install:
- Download the installer from [Swift](https://www.swift.org/install/windows/).
- Once downloaded, run the installer.
- Verify Installation:
```bash
swift --version
```

---

### 2. Execution:
```bash
swift helloworld.swift
```

- If there are any issues (like not being able to find certain symbols during the Just-In-Time (JIT) compilation process) while executing with the command, run the below commands:
```bash
swiftc HelloWorld.swift -o HelloWorld # Compilation

./HelloWorld # Execution
```

- **swiftc** is the Swift compiler, which compiles your .swift file into a standalone executable. 
- This avoids the need for JIT compilation, which can sometimes fail due to missing symbols or runtime issues. 
- And produces an executable file.

---

### 3. Output:
```bash
Hello World...!!!
```