# 🧱 Context Blocks

Reusable context snippets to feed into AI agents for better grounding, accuracy, and consistency.

---

## 🧩 Project Metadata

```json
{
  "project": "MyApp",
  "framework": "React 18",
  "language": "TypeScript",
  "stateManagement": "Redux Toolkit",
  "testing": ["Jest", "React Testing Library"],
  "deployment": "GitHub Pages"
}
```

---

## 🎨 Style Guide

```markdown
- Use camelCase for variables and functions
- Use PascalCase for components and classes
- Prefer arrow functions over function declarations
- Use `const` and `let` (no `var`)
- Always include TypeScript interfaces for props and state
- Avoid `any` types; use specific types or generics
```

---

## 🔌 API Reference

```yaml
GET /api/users
- Returns a list of users
- Requires Authorization header
- Response: 200 OK
  [
    {
      "id": "string",
      "name": "string",
      "email": "string"
    }
  ]
```

---

## 🧪 Testing Strategy

```markdown
- Unit tests for all utility functions and components
- Integration tests for API endpoints
- End-to-end tests for critical user flows
- 90%+ test coverage required
- Mock external services using MSW or Jest mocks
```

---

## 🔐 Security Policy

```markdown
- Sanitize all user inputs
- Use HTTPS for all endpoints
- Store secrets in environment variables (never in code)
- Use JWTs with expiration and refresh tokens
- Validate all API payloads against a schema (e.g., Zod)
```

---

## 🧠 Prompt Context Example

```markdown
You are a CoderAgent working on a React + TypeScript project. Your task is to generate a new component based on the following spec. Follow the style guide and ensure the code is testable and readable.
```

---

## 📌 Tips

- Keep context blocks under 1,000 tokens when possible.
- Use structured formats (JSON, YAML, Markdown) for clarity.
- Update context blocks as your stack evolves.
