# C Hello World

## 1. How to Install
### Install a COBOL Compiler (GnuCOBOL)  
GnuCOBOL is an open-source COBOL compiler that works on macOS. 
Install it using Homebrew:  
```bash
brew install gnu-cobol
```

Verify installation:
```bash
cobc -v
```

---

## 2. How to Run
1. **Compile the COBOL Program**:
   Use cobc (GnuCOBOL compiler) to compile your program:  
   ```bash
   cobc -x HelloWorld.cob -o HelloWorld
   ```
2. **Execute the compiled program:**:
   ```bash
   ./HelloWorld
   ```

---

## 3. Output
```
Hello, World!
```  

## 4. References:  
[1. Installing COBOL-IDE](https://www.geeksforgeeks.org/how-to-install-cobol-on-macos/)  
[2. OpenCOBOL Manual ](https://gnucobol.sourceforge.io/historical/open-cobol/index.html#Top)  