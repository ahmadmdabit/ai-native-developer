### 📄 templates/prompt-library.md

# 🧠 Prompt Library

A curated collection of reusable, high-quality prompts for AI agents across the software development lifecycle. Use these as-is or customize them for your stack.

---

## 📦 Code Generation

### Generate a React Component
```text
Write a functional React component named `{{ComponentName}}` that accepts the following props: {{PropsList}}. It should render {{ComponentBehavior}}. Use TypeScript and include PropTypes.
````

### Create a REST API Endpoint

```text
Generate an Express.js route handler for `POST /{{endpoint}}` that accepts a JSON payload with {{fields}} and stores it in a MongoDB collection named `{{collectionName}}`.
```

---

## 🧪 Test Generation

### Unit Tests for a Function

```text
Write unit tests using Jest for the following JavaScript function. Cover edge cases and invalid inputs. Ensure 100% branch coverage.
```

### Integration Test for API

```text
Generate an integration test using Supertest for the `GET /api/{{resource}}` endpoint. Validate response status, schema, and edge cases.
```

---

## 🧹 Refactoring & Optimization

### Refactor for Readability

```text
Refactor the following code to improve readability and maintainability. Use clear variable names, extract helper functions, and remove duplication.
```

### Optimize for Performance

```text
Optimize the following function for performance. Avoid unnecessary computations and reduce time complexity where possible.
```

---

## 📚 Documentation

### Function Docstring

```text
Write a Python docstring for the following function using Google-style format. Include a description, arguments, return value, and example usage.
```

### Component Documentation

```text
Generate Markdown documentation for the `{{ComponentName}}` React component, including props, usage example, and expected behavior.
```

---

## ⚙️ DevOps & CI/CD

### GitHub Actions Workflow

```text
Create a GitHub Actions workflow that runs tests on push to `main`, builds the app, and deploys it to GitHub Pages.
```

### Dockerfile Generator

```text
Generate a Dockerfile for a Node.js app using `npm start`. Include best practices for caching and security.
```

---

## 🛡️ Security & Validation

### Input Sanitization

```text
Add input validation and sanitization to the following Express.js route to prevent XSS and injection attacks.
```

### Secure Authentication Flow

```text
Generate a secure login flow using JWTs in a Node.js + Express backend. Include token expiration and refresh logic.
```

---

## 🧠 Prompt Engineering Meta

### Prompt Debugging

```text
Analyze the following prompt and suggest improvements to make it more specific, deterministic, and safe.
```

---

## 📌 Tips

- Use double curly braces `{{ }}` for placeholders.
- Keep prompts short, specific, and goal-oriented.
- Include constraints (e.g., language, framework, format) when needed.
