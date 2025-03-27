# University-GPA-Calculator
*A command-line Python tool for automated GPA calculation with multi-scale support.*

---

## Motivation
As a student managing multiple semesters, manual GPA calculation become error-prone and time-comsuming. This project solves three core problems:
1. **Accuracy**: Eliminate human error in GPA computation.
2. **Flexibility**: Support diverse grading system (4.0/4.3 scales)
3. **Portability**: Lightweight CLI tool for quick academic audits.

---

## Features
- 📊**Dynamic Input Handling**
  - Add courses interactively with credits/letter grades.
  - Support for +/- grades (e.g., A-, B+)
- ⚖️**Multi-Scale Calculation**
  - Switch between 4.0 (standard) and 4.3 (weighted) GPA systems.
- ✅**Data Validation**
  - Regex-based grade
  - Credit range validation (0.0-4.0 | 0.0-4.3)
- 📤**Result Export**
  - Save transcript to '.txt' file.
