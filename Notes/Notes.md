Computer Organization and Architecture
======================================

-   **What is a computer?**

    -   Runs on set of instructions.
    -   Ability to store massive amount of information.
    -   Processes large amount of data in a relative short amount
        of time.

-   **Bare essentials**

    -   Take an input.
    -   Produce an input.
    -   Have some kind of information storage.
    -   Processing of information.
    -   Have way to control what it does.

-   **Organization & Architecture**

    -   **Organization (How it works)**

        -   How is it controlled?
        -   Signal design
        -   Memory type
        -   Physical: circuit components
        -   Physics

    -   **Architecture (How it’s designed)**

        -   Logic and abstraction
        -   Instructions set, operation codes, and data types
        -   Memory access and input/output

-   **History of Computers**

  | Type                                   | Period          | Performance  |
  | ---------------------------------------| ----------------| -------------|
  | Mechanical Computers                   | 1630-1945       | &lt;1        |
  | Vacuum Tubes                           | 1945-1955       | 1            |
  | Transistor                             | 1955-1965       | 35           |
  | Integrated circuit                     | 1965-1980       | 900          |
  | LSI (Large System Integration) & VLSI  | 1980 – Present  | 2,400,000    |

-   **Computer Layers**
    -   User
    -   High-level Language – Java, C++, Python
    -   Assembly Language – Assembly Code
    -   System Software - OS
    -   Machine
    -   Control – Hard wired
    -   Digital Logic – Basic components
    -   Physics

-   **The Three -y's**

    - Hierarchy
        - A system divided into modules and submodules.

    - Modularity
        - Having well-defined functions and interfaces.

    - Regularity
        - Encouraging uniformity, so modules can be easily reused.


-   **The Digital Abstraction**
    - Most physical variables are continuous.
    - Digital abstraction considers discrete subset of values.

- **A logic circuit is composed of:**
    - Inputs
    - Outputs
    - Functional specification
    - Timing specification

-  **Types of Logic Circuits**
    - **Combinational Logic**
        - Memoryless
        - Outputs determined by current values of inputs.
    - **Sequential Logic**
        - Has memory  
        - Outputs determined by previous and current values of inputs.

- **Rules of Combinational Composition**
    - Every element is combinational.
    - Every node is either an input or connects to exactly one output.

- **Boolean Equations**
    - Functional specification of outputs in terms of inputs.
    - **Sum-of-Products (SOP) Form**
        - All equations can be written in SOP form.
        - Each row has a **minterm**.
        - A minterm is a product (AND) of literals.
        - Each minterm is **TRUE** for that row (and only that row).
        - Form function by ORing minterms where output is 1.
        - Thus, a sum (OR) of products (AND terms).
    - **Products-of-Sum (POS) Form**
        - All boolean equations can be written in POS form.
        - Each row has a **maxterm**.
        - A maxterms is a sum (OR) of literals.
        - Each maxterm is **FALSE** for that row (and only that row).
        - Form function by ANDing minterms where output is 0.
        - Thus, a product (AND) of sums (OR terms).

- **Boolean Algebra**
    - Axioms and theorems to **simplify** Boolean equations.
    - Like regular algebra, but simpler: variables have only two values(1 or 0).
