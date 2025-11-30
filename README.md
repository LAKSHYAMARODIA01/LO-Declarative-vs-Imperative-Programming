# **Declarative vs Imperative Programming — Hello World Assignment**

This repository demonstrates the core difference between **Imperative** and **Declarative** programming paradigms by building the same small application in two different ways.
Both versions output **“Hello, World!”** on a webpage, while showcasing how each paradigm approaches UI creation.

---

## 📁 **Project Structure**

```
.
├── imperative-hello-world/
│   ├── index.html
│   └── script.js
│
└── declarative-hello-world/
    ├── index.html
    └── app.js
```

Each folder represents one paradigm with its own implementation.

---

# **1. Imperative Approach (Vanilla JavaScript)**

### 📂 Folder: `imperative-hello-world`

The Imperative style focuses on **how to perform each step**.
In this version, we manually create and append DOM elements using JavaScript.

### ✔ Key Characteristics

* Direct DOM manipulation
* Step-by-step instructions
* Explicit element creation and insertion

### 📄 Code Snippet (`script.js`)

```javascript
const p = document.createElement("p");
p.textContent = "Hello, World!";
document.body.appendChild(p);
```

This approach tells the browser exactly what to do at each stage.

---

# **2. Declarative Approach (React)**

### 📂 Folder: `declarative-hello-world`

The Declarative style focuses on **what the UI should look like**, leaving React to handle the DOM operations internally.

### ✔ Key Characteristics

* UI is described, not manually constructed
* React handles DOM updates
* Clean and minimal code with JSX

### 📄 Code Snippet (`app.js`)

```javascript
const element = <p>Hello, World!</p>;

ReactDOM.createRoot(document.getElementById("root")).render(element);
```

React interprets the declared UI and efficiently renders it to the DOM.

---

# **🎯 Key Difference Explained**

| Paradigm        | Explanation                                                         |
| --------------- | ------------------------------------------------------------------- |
| **Imperative**  | You specify *how* the UI should be built (manual DOM manipulation). |
| **Declarative** | You specify *what* the UI should look like (React handles the DOM). |

Both produce identical output but follow fundamentally different programming philosophies.

---

# **🚀 Running the Projects**

### **Imperative Version**

1. Open `imperative-hello-world/index.html` in your browser.

### **Declarative Version**

1. Open `declarative-hello-world/index.html`.
2. Ensure you have an internet connection (React CDN loaded via script tags).

---

# **📄 Assignment Context**

This repository is created as part of the **Masai School** assignment for the Learning Objective:

### **“Difference Between Declarative and Imperative Programming”**

The project demonstrates both paradigms clearly with minimal and focused examples.

---

# **📬 Author**

**Lakshya Marodia**
