# 🧭 Copilot Code Review Instructions

These are the custom rules that GitHub Copilot must follow when reviewing code in this repository.  
Copilot should apply these rules to **every pull request** and **every code review request**.

---

## 🔧 Error Handling
- Always check that methods validate inputs.
- Ensure that code handles invalid data or potential failures.
- If a method can throw an exception, verify that it uses proper error handling (e.g., validation or try-catch).
- Request changes if code assumes inputs are always valid.

---

## 🧱 Naming Conventions (C#)
- All class names, method names, and public members must use **PascalCase**.
- Flag any occurrences of snake_case, camelCase, or inconsistent naming.

---

## 📝 Code Comments
- Important methods must include a short description explaining their purpose.
- Request improvements if comments are missing, unclear, or unhelpful.

---

## 🖨️ Console Logging
- Console output must be meaningful and descriptive.
- If `Console.WriteLine` is used, the message must clearly explain what is being logged.
- Flag vague messages such as: “Done”, “Here”, “Test”, or other unclear outputs.

---

## ✨ Clean & Readable Code
- Code must be clean, readable, and well formatted.
- Look for messy layout, confusing logic, poor indentation, or inconsistent spacing.
- Request improvements where needed.

---

## ♻️ Code Duplication
- Identify repeated or duplicated code across methods, classes, or files.
- Suggest extracting shared logic into reusable helper methods or services.

---

### ✅ End of Copilot instructions
Copilot should follow these rules in every code review in this repository.
