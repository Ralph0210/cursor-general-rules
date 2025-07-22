# cursor-general-rules
Here’s a simple README you can use for your `.cursor/rules` repository:

---

# Cursor Rules

This directory contains a collection of **Cursor Rules** to help maintain high standards for frontend development, UI/UX design, accessibility, UX writing, and team collaboration in this project.

## 📁 How Cursor Rules Work

- **Location:**  
  All rules are stored in the `.cursor/rules/` directory at the root of the project.

- **Format:**  
  Each rule is a Markdown file with a `.mdc` extension (e.g., `accessibility.mdc`).  
  Rules use Markdown with special frontmatter for metadata.

- **Purpose:**  
  These rules are automatically shown to the Cursor AI tool to guide code generation, reviews, and best practices.  
  They help ensure consistency, quality, and collaboration across the codebase.

## 📝 Rule Structure

Each rule file contains:
- **Frontmatter:**  
  Controls how and when the rule is applied (e.g., `alwaysApply`, `globs`, `description`).
- **Guidelines:**  
  The main content, written in Markdown, describing best practices or standards.

**Example:**
```markdown
---
alwaysApply: true
description: Accessibility guidelines for all frontend code.
globs: *.js,*.jsx,*.ts,*.tsx,*.css,*.scss,*.html
---

# Accessibility (a11y) Guidelines

- Use semantic HTML elements for structure and meaning.
- Ensure all interactive elements are keyboard accessible.
- Provide visible focus indicators for keyboard navigation.
...
```

## 🛠️ How to Use

1. **Edit or add rules** in `.cursor/rules/` as needed for your project.
2. **Cursor AI** will automatically use these rules to guide its suggestions and code generation.
3. **Update rules** as your team’s standards or workflows evolve.

## 📚 Included Rules

- Frontend Development Best Practices
- UI/UX Design Best Practices
- UX Writing Best Practices
- Accessibility Guidelines
- Performance Optimization
- State Management
- Testing & QA
- Documentation
- Code Review & Collaboration
- Security Best Practices
- Planning & Collaboration Process

## ✨ Why Use Cursor Rules?

- **Consistency:** Ensures everyone follows the same standards.
- **Quality:** Reduces bugs and improves maintainability.
- **Collaboration:** Makes it easier for new team members and AI tools to understand your workflow.

---

Feel free to copy, modify, and expand these rules to fit your team’s needs!

---
