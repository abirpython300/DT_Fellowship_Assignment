# DT_Fellowship_Assignment
A deterministic reflection tool that guides users through structured daily self-assessment using a decision tree. It evaluates behavior across control, contribution, and perspective without using AI at runtime, ensuring consistent and interpretable insights.
# 🌳 Daily Reflection Tree — Deterministic Reflection Agent

## 📌 Overview

This project implements a **deterministic end-of-day reflection system** that guides users through structured self-assessment without using any AI at runtime.

Instead of a chatbot, the system uses a **decision tree** where:
- Users select from fixed options
- The system follows predefined paths
- Reflections are generated using structured logic

The goal is to demonstrate how **human psychology can be encoded into a navigable, auditable system**.

---

## 🧠 Core Concept

The reflection flow is built across three psychological axes:

1. **Locus of Control (Victim vs Victor)**  
   → Did the user perceive control over their day?

2. **Contribution vs Entitlement**  
   → Did the user focus on giving or expecting?

3. **Radius of Concern (Self vs Others)**  
   → Was the user focused on self or broader impact?

Each axis builds on the previous one, forming a **progressive reflection journey**.

---

## ⚙️ Key Features

- ✅ Fully deterministic (no randomness, no LLM calls)
- ✅ Fixed multiple-choice inputs (no free text)
- ✅ Structured decision tree (data-driven)
- ✅ Signal tracking across psychological axes
- ✅ Dynamic reflection using template interpolation
- ✅ Reproducible and auditable outputs

---

## 🗂️ Project Structure
