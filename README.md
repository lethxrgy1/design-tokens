# 🎨 Design Tokens Repository

This private repository contains platform-agnostic design tokens exported from [Tokens Studio](https://tokens.studio/). These tokens define the foundational design language—such as color, typography, spacing, and more—used consistently across our digital products.

---

## 📦 Structure


---

## 🧩 What Are Design Tokens?

Design tokens are the visual design atoms of the design system – small, reusable pieces such as:

- 🎨 **Colors** (e.g., `color.background.primary`)
- 🔤 **Typography** (e.g., `font.size.body`, `font.family.base`)
- 📐 **Spacing** (e.g., `spacing.medium`)
- 🟦 **Border radius** (e.g., `radius.small`)
- 🕶 **Shadows, opacity, breakpoints**, and more

They allow designers and developers to share a single source of truth.

---

## 🔁 Workflow

### 1. **Design → Token Update**
Designers update and sync tokens using Tokens Studio in Figma.

### 2. **Token Sync**
Tokens are exported from Tokens Studio and committed to the `tokens/` directory in this repo (usually as JSON files).

### 3. **Optional: Build Pipeline**
Tokens can be transformed for use in various platforms (Web, iOS, Android, etc.) using tools like [Style Dictionary](https://amzn.github.io/style-dictionary/#/).

---

## 🛠 Tooling

- **Tokens Studio** – Design-side token creation and management
- **Style Dictionary (optional)** – Transform tokens into platform-specific formats
- **GitHub Actions (optional)** – Automate syncs, builds, or validations

---

## 📄 Usage

TBD
