# Polygon Area Calculator (freeCodeCamp Project)

A geometric computational library engineered in Python utilizing robust Object-Oriented Programming (OOP) architectures, specifically showcasing **Class Inheritance** and **Method Overriding**. The application models rectangles and squares to calculate mathematical profiles, scale shapes dynamically, render shapes as ASCII text fields, and evaluate nesting limits.

This project successfully completes 100% of the operational parameters required by the **freeCodeCamp Python Certification** program.

## 📐 Project Objectives & Subclass Architecture
1. **Base Class (`Rectangle`):** Encapsulates core width and height states with operational calculations including `.get_area()`, `.get_perimeter()`, and `.get_diagonal()`.
2. **Inherited Subclass (`Square`):** Inherits all structural methods from `Rectangle` while constraining the system to maintain matching 1:1 width-to-height spatial ratios.
3. **Method Overriding:** Intercepts parent configuration calls (`set_width` and `set_height`) within the subclass environment to enforce uniform side-length updates.
4. **ASCII Render Engine (`get_picture`):** Generates strict text visual structures utilizing loop-free string multiplications, protected by a safety ceiling for large inputs.
5. **Nesting Matrix Solver (`get_amount_inside`):** Executes flawless floor-division equations to map coordinate capacity without rotating the dimensions.

## 🛠️ Core Technical Concepts Demonstrated
* **Polymorphism & Inheritance:** Harnessing `super()` linkages to construct highly reusable parent-child data entities.
* **Encapsulation Protection:** Overriding native tracking properties to guarantee absolute model consistency under mutation calls.
* **String Overrides (`__str__`):** Modifying underlying Python string outputs to map customized debug states back into cleanly formatted class records.

## 📂 Code Layout Map
* `main.py`: The production library housing the polymorphic classes (`Rectangle` and `Square`).
* `README.md`: Formal administrative project blueprint documentation.
