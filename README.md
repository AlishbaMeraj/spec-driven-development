<p align="center">
  <img src="https://img.shields.io/badge/Spec--Driven-Workflow-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/AI--Assisted-Development-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-informational?style=flat-square" />
</p>

<h1 align="center">Spec-Driven Development ⚙️</h1>
<p align="center"><em>Think it through. Write it down. Let AI build it right.</em></p>

---

## 🌱 What this is about

Spec-Driven Development is a way of building software where **clear written specs come first**.  
Instead of starting with code or loose prompts, you describe the system in plain language and let AI handle the implementation.

The goal is simple: **less guesswork, more consistency**.

---

## 📁 What lives in this folder

- 🧾 `constitution.md`  
  Defines rules, standards, and engineering principles

- 📄 `spec.md`  
  Explains what the feature should do and how success is measured

- 🧠 `plan.md`  
  Outlines architecture, tools, and technical decisions

- ✅ `tasks.md`  
  Breaks the work into small, testable steps

---

## 🔁 How the workflow runs

| Phase | Command |
|------|--------|
| Constitution | `/sp.constitution` |
| Specification | `/sp.specify` |
| Planning | `/sp.plan` |
| Tasks | `/sp.tasks` |
| Implementation | `/sp.implement` |

Each step produces clear input for the next—nothing is left implicit.

---

## 🧪 Quality comes built-in

Implementation follows **Test-Driven Development**  
(Red → Green → Refactor), so AI-generated code stays reliable and easy to change.

---

## ⚡ Getting started quickly

```bash
pip install specifyplus
specifyplus init my-project --ai claude
