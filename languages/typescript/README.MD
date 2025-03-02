# TypeScript Hello World

## 1. How to Install
1. Install **Node.js** from [nodejs.org](https://nodejs.org/).
2. Install TypeScript globally:
   ```bash
   npm install -g typescript
   ```
3. Verify:
   ```bash
   tsc --version  # Should show TypeScript 5.x+
   ```

---

## 2. How to Run
1. **Compile** TypeScript to JavaScript:
   ```bash
   tsc hello.ts
   ```
   This generates `hello.js`.

2. **Execute** the compiled JavaScript:
   ```bash
   node hello.js
   ```

---

## 3. Output
```
Hello, World!
```

---

### Notes:
- TypeScript adds static typing to JavaScript.
- Requires compilation to JavaScript before execution.
- Works with **Node.js 18+** and modern browsers (with a build step).
