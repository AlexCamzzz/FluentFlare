# 🔥 FluentFlare
### A modern English-learning platform powered by dynamic, programmable activities.

**FluentFlare** is an interactive language-learning platform designed to help students build English proficiency through short, structured lessons and dynamic activity types.  
The system focuses on clean UI, flexible content creation, and a modular activity engine capable of scaling to thousands of exercises without rewriting components.

This project serves as a practical demonstration of:
- Modern frontend development (Vue 3 + TailwindCSS)
- Dynamic content rendering using JSON-driven activity blueprints
- Clean architecture for scalable educational platforms
- Branding, UI/UX design, and full-stack integration

It is currently under active development as an MVP.

---

## ✨ Key Features

### 🧩 Dynamic Activity Engine
FluentFlare activities are generated using a **blueprint system**:

- `activityType` — defines the component/logic
- `payload` — JSON content for that specific activity
- `level` — CEFR level (A1–C2)
- `skill` — grammar, vocabulary, listening, etc.

This allows:
- Creating new activities **without changing code**
- Rapid content expansion
- Reusable UI components
- Separation of logic and content

**Example:**

```json
{
  "activityType": "multiple_choice",
  "level": "A2",
  "payload": {
    "question": "Choose the correct answer",
    "choices": ["He go", "He goes", "He going"],
    "correctIndex": 1
  }
}
