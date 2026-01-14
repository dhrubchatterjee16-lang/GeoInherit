# 📐 GeoInherit: Python OOP Shape Hierarchy

A clean, educational demonstration of **Object-Oriented Programming (OOP)** principles in Python. This project showcases how to use **Class Inheritance** and the `super()` function to create a organized hierarchy of geometric shapes.



## 🧠 Concepts Covered

* **Parent vs. Child Classes:** Using a base `Shape` class to store common attributes (color, fill status).
* **Inheritance:** How `Circle`, `Square`, and `Triangle` inherit properties from `Shape`.
* **The `super()` Function:** Properly initializing parent attributes within child constructors.
* **Encapsulation:** Storing data specific to each shape (like radius or width).

## 🚀 How It Works

The project defines a core `Shape` class. All specific shapes then "inherit" from it:

| Class | Unique Attributes | Inherited Attributes |
| :--- | :--- | :--- |
| **Shape** | - | `color`, `is_filled` |
| **Circle** | `radius` | `color`, `is_filled` |
| **Square** | `width` | `color`, `is_filled` |
| **Triangle** | `width`, `height` | `color`, `is_filled` |


   git clone [https://github.com/your-username/GeoInherit.git](https://github.com/your-username/GeoInherit.git)
