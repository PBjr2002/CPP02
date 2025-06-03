# CPP 02

## Project Overview

**CPP 02** introduces the Orthodox Canonical Form for class design, emphasizing the implementation of the four essential member functions: default constructor, copy constructor, copy assignment operator, and destructor.

This project focused on:

- Designing classes following the Orthodox Canonical Form
- Adding conversions between integer, floating-point, and fixed-point representations
- Overloading arithmetic and comparison operators
- Creating increment/decrement operators with precise value changes
- Implementing static member functions for min/max comparisons
- Using operator overloading for output streaming

---

### Exercise 00: My First Class in Orthodox Canonical Form  
**Goal:** Create a fixed-point number class implementing the Orthodox Canonical Form with basic functionality to store and access raw fixed-point data.

**Key concepts:**  
- Orthodox Canonical Form (default constructor, copy constructor, copy assignment operator, destructor)
- Class member encapsulation
- Private static constants

---

### Exercise 01: Towards a more useful fixed-point number class  
**Goal:** Enhance the fixed-point class with constructors for integer and floating-point inputs, conversion methods, and stream insertion operator overloading.

**Key concepts:**  
- Overloading constructors for different input types
- Converting between fixed-point and primitive types (int, float)
- Operator overloading for output streams (`<<`)
- Using `roundf` for accurate conversions

---

### Exercise 02: Now we’re talking
**Goal:** Add operator overloads for comparison, arithmetic, and increment/decrement operations, plus static member functions for min/max comparisons.

**Key concepts:**
- Overloading comparison operators: `>`, `<`, `>=`, `<=`, `==`, `!=`
- Overloading arithmetic operators: `+`, `-`, `*`, `/`
- Overloading pre- and post- increment/decrement operators
- Implementing static member functions for minimum and maximum selection
- Precision handling with the smallest representable increments
