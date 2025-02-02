
### **1. What is JavaScript?**
JavaScript is a **high-level**, **interpreted** programming language used to make web pages interactive. It runs in the browser and allows you to:
- Add dynamic behavior to websites (e.g., animations, form validation).
- Manipulate the DOM (Document Object Model) to change content on the fly.
- Communicate with servers (APIs) to fetch or send data.

---

### **2. Setting Up JavaScript**
You can write JavaScript in:
1. **HTML File** (inside `<script>` tags):
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>My First JS</title>
   </head>
   <body>
       <script>
           console.log("Hello, World!");
       </script>
   </body>
   </html>
   ```
2. **External JS File** (linked to HTML):
   ```html
   <script src="script.js"></script>
   ```
   In `script.js`:
   ```javascript
   console.log("Hello from an external file!");
   ```
3. **Browser Console** (for quick testing):
   - Open your browser (Chrome, Firefox, etc.).
   - Press `F12` or `Ctrl + Shift + I` to open Developer Tools.
   - Go to the **Console** tab and start typing JavaScript.

---

### **3. Variables**
Variables are used to store data. In JavaScript, you can declare variables using:
- `let`: For variables that can change.
- `const`: For variables that cannot change (constants).
- `var`: Older way (avoid for now).

#### Example:
```javascript
let name = "Alice"; // Can be changed
const age = 25;     // Cannot be changed
console.log(name);  // Output: Alice
console.log(age);   // Output: 25
```

#### Rules for Variable Names:
- Must start with a letter, `_`, or `$`.
- Cannot start with a number.
- Case-sensitive (`myVar` ≠ `myvar`).
- camelCase Convention.

---

### **4. Data Types**
JavaScript has several basic data types:
1. **String**: Text (e.g., `"Hello"`).
2. **Number**: Integers or decimals (e.g., `10`, `3.14`).
3. **Boolean**: `true` or `false`.
4. **Null**: Represents no value.
5. **Undefined**: Variable declared but not assigned.
6. **Array**: Ordered list of values (e.g., `["Apple","Banana", "Cherry"]`).
7. **Object**: Collections of key-value pairs (e.g., `{ name: "Alice", age: 25 }`).

#### Example:
```javascript
let name = "Alice";       // String
let age = 25;             // Number
let isStudent = true;     // Boolean
let job = null;           // Null
let salary;               // Undefined
let fruits = ["Apple","Banana", "Cherry"]; //Array
let person = {            // Object
    name: "Alice",
    age: 25
};
```

---

### **5. Operators**
Operators are used to perform operations on variables and values.

#### Types of Operators:
1. **Arithmetic**: `+`, `-`, `*`, `/`, `%` (modulus).
   ```javascript
   let sum = 10 + 5; // 15
   let remainder = 10 % 3; // 1
   ```
2. **Comparison**: `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`.
   ```javascript
   console.log(10 == "10"); // true (loose equality)
   console.log(10 === "10"); // false (strict equality)
   ```
3. **Logical**: `&&` (AND), `||` (OR), `!` (NOT).
   ```javascript
   console.log(true && false); // false
   console.log(true || false); // true
   console.log(!true); // false
   ```

---

### **6. Comments**
Comments are used to explain your code. They are ignored by the browser.

#### Types of Comments:
1. **Single-line**:
   ```javascript
   // This is a single-line comment
   let x = 10;
   ```
2. **Multi-line**:
   ```javascript
   /*
   This is a multi-line comment.
   It can span multiple lines.
   */
   let y = 20;
   ```

---

### **7. Your First Program**
Let’s write a simple program to combine what we’ve learned:
```javascript
// Declare variables
let name = "Alice";
let age = 25;
let isStudent = true;

// Print to console
console.log("Name: " + name);
console.log("Age: " + age);
console.log("Is Student: " + isStudent);

// Perform a calculation
let birthYear = 2023 - age;
console.log("Birth Year: " + birthYear);
```

---
