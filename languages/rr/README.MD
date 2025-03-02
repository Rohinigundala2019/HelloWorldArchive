# R Hello World

## 1. How to Install
### Linux (Debian/Ubuntu):
```bash
sudo apt update && sudo apt install r-base
```

### macOS:
1. Download R from [CRAN](https://cran.r-project.org/bin/macosx/).
2. Install the `.pkg` file.

### Windows:
1. Download R from [CRAN](https://cran.r-project.org/bin/windows/base/).
2. Run the installer.

Verify installation:
```bash
R --version
```

---

## 2. How to Run
### From the command line:
```bash
Rscript hello.R
```

### Alternatively, in an R interactive session:
1. Launch R:
   ```bash
   R
   ```
2. Run:
   ```r
   source("hello.R")
   ```

---

## 3. Output
```
Hello, World!
```

---

### Notes:
- The `quote = FALSE` argument removes quotation marks from the output.
- Works with **R 3.0+** (tested on R 4.3.1).