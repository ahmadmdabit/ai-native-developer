# 🧠 Prompt Library

A curated collection of reusable, high-quality prompts for AI agents across the software development lifecycle. Use these as-is or customize them for your stack.

---

## 📦 Code Generation

### Generate a React Component

```text
Write a functional React component named `{{ComponentName}}` that accepts the following props: {{PropsList}}. It should render {{ComponentBehavior}}. Use TypeScript interfaces for props. Ensure the component is accessible (A11y compliant) and handles loading/error states.
```

### Create a REST API Endpoint

```text
Generate an Express.js route handler for `POST /{{endpoint}}` that accepts a JSON payload with {{fields}} and stores it in a MongoDB collection named `{{collectionName}}`. Include input validation using Zod and proper error handling.
```

---

## 🧪 Test Generation

### Unit Tests for a Function

```text
Write unit tests using Jest for the following JavaScript function. Cover edge cases, invalid inputs, and happy paths. Ensure 100% branch coverage. Mock any external dependencies.
```

### Integration Test for API

```text
Generate an integration test using Supertest for the `GET /api/{{resource}}` endpoint. Validate response status, JSON schema, and error scenarios (401, 404, 500).
```

---

## 🧹 Refactoring & Optimization

### Refactor for Readability

```text
Refactor the following code to improve readability and maintainability. Use clear variable names, extract helper functions, and remove duplication (DRY principle). Do not change the business logic.
```

### Optimize for Performance

```text
Optimize the following function for performance. Identify bottlenecks (O(n^2) or worse), avoid unnecessary computations, and reduce time complexity where possible. Explain your changes.
```

---

## 📚 Documentation

### Function Docstring

```text
Write a Python docstring for the following function using Google-style format. Include a description, arguments, return value, raises, and an example usage block.
```

### Component Documentation

```text
Generate Markdown documentation for the `{{ComponentName}}` React component. Include:
1. Description
2. Props table (Name, Type, Description)
3. Usage example
4. Edge cases
```

---

## ⚙️ DevOps & CI/CD

### GitHub Actions Workflow

```text
Create a GitHub Actions workflow that runs tests on push to `main`, builds the app, and deploys it to GitHub Pages. Include caching for `node_modules` to speed up builds.
```

### Dockerfile Generator

```text
Generate a multi-stage Dockerfile for a Node.js app. Stage 1: Build. Stage 2: Production run (using `npm start`). Include best practices for layer caching and running as a non-root user for security.
```

---

## 🛡️ Security & Validation

### Input Sanitization

```text
Add input validation and sanitization to the following Express.js route to prevent XSS and SQL/NoSQL injection attacks. Use a validation library like `express-validator` or `Joi`.
```

### Secure Authentication Flow

```text
Generate a secure login flow using JWTs in a Node.js + Express backend. Include password hashing (bcrypt), token expiration, and refresh token logic.
```

---

## 🧠 Prompt Engineering Meta

### Prompt Debugging

```text
Analyze the following prompt and suggest improvements to make it more specific, deterministic, and safe. Identify any ambiguity that could lead to hallucinations.
```

---

## 📌 Tips

- Use double curly braces `{{ }}` for placeholders.
- Keep prompts short, specific, and goal-oriented.
- Include constraints (e.g., language, framework, format) when needed.
