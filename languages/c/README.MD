# C Hello World

## 1. How to Install
### Linux
```bash
sudo apt update && sudo apt install build-essential
```

### macOS
Install Xcode Command Line Tools:
```bash
xcode-select --install
```

### Windows
1. Download [MinGW](http://www.mingw.org/).
2. Add `C:\MinGW\bin` to your system `PATH`.

Verify installation:
```bash
gcc --version
```

---

## 2. How to Run
1. **Compile the Program**:
   ```bash
   gcc hello-world.c -o hello.out
   ```
2. **Execute the Binary**:
   ```bash
   ./hello
   ```

---

## 3. Output
```
Hello, World!
```