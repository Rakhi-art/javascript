# JavaScript Basics – How JavaScript Works

JavaScript (JS) is a programming language used to make web pages interactive.  
HTML builds the structure, CSS handles the design, and JavaScript adds life to the webpage.

---

## 🚀 What is JavaScript?

JavaScript is a **client-side scripting language** that runs in the browser.  
It allows you to:
- Show alerts
- Change text or images
- Respond to user actions (click, input, hover)
- Validate forms
- Create animations and dynamic content

---

## ⚙️ How JavaScript Works

When a webpage loads:
1. **HTML loads first**
2. **CSS is applied**
3. **JavaScript executes last**

The browser has a **JavaScript Engine** (Chrome → V8, Firefox → SpiderMonkey) that:
- Reads JavaScript code  
- Converts it into machine code  
- Executes it line by line  

JS uses an **Event Loop**, meaning it runs code synchronously and handles events (clicks, network requests) asynchronously.

---

## 📂 How to Add JavaScript in HTML

✔️ Internal JavaScript

<script>
    console.log("Hello from JS!");
</script>

✔️ External JavaScript (Recommended)

<script src="script.js"></script>

🧠 Basic Example

document.getElementById("btn").addEventListener("click", function() {
    alert("Button Clicked!");
});

index.html

<button id="btn">Click Here</button>
<script src="script.js"></script>

🔄 How JS Interacts With HTML (DOM)

The DOM (Document Object Model) is a tree-like structure of your webpage.

JavaScript can:

Change text
document.getElementById("title").textContent = "New Title";

Change styles
document.body.style.background = "lightblue";

Create elements
const p = document.createElement("p");
p.textContent = "Hello!";
document.body.appendChild(p);

🧩 Features of JavaScript

Dynamic typing

Supports OOP

Widely used in frontend & backend (Node.js)

Huge ecosystem (React, Angular, Vue)

📗 Conclusion

JavaScript is the backbone of modern web development.
It makes web pages interactive and powerful by manipulating HTML, handling events, and running logic through the browser’s engine and event loop.
