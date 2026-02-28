```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the principles and constraints for the development of AI coding agents. Adherence to these principles is crucial for maintaining a clean, maintainable, and reliable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Code Reuse:**  Design modules and components to be reusable across multiple agents or related functionalities.  Avoid duplicating logic within individual files.
*   **Parameterization:**  Wherever possible, encapsulate parameters and logic within functions and classes, making them easily configurable.
*   **Consistent Naming Conventions:** Establish and enforce consistent naming conventions throughout the codebase.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimalism:**  Strive for the simplest possible solution that achieves the desired outcome. Avoid over-engineering.
*   **Readability:** Code should be easy to understand, even by non-experts. Use clear variable names, comments, and formatting.
*   **Efficiency:** Prioritize efficient algorithms and data structures. Avoid unnecessary computations.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  The system should be extensible – new functionality should be added without modifying existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on implementation details.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Don’t introduce features or logic that are not currently required. Resist the urge to build functionality that may never be used.
*   **Focus on Requirements:** Prioritize implementing the required functionality based on the defined requirements.

## 5. Code Structure & File Limits

*   **Maximum Code Length:** Each file must not exceed 180 lines of code.
*   **File Organization:**  Maintain a clear hierarchical structure within each file, reflecting the logical grouping of the code.
*   **Modular Design:**  Break down the codebase into well-defined modules with clear responsibilities.
*   **Layered Architecture:** Implement a layered architecture where modules and components have clearly defined interfaces.

## 6. Testing & Verification

*   **Comprehensive Tests:** All code must be thoroughly tested using provided mocks.
*   **Unit Tests:**  Each module/class should have a suite of unit tests covering its core functionality.
*   **Integration Tests:**  Integrate the module with other components to verify the overall system behavior.
*   **Test Coverage:** Aim for 80% test coverage across all modules and functions.

## 7. Development Process

*   **Code Reviews:**  All code must undergo peer review before being merged into the main branch.
*   **Static Analysis:** Employ static analysis tools to identify potential errors and violations of coding standards.
*   **Version Control:**  Strictly adhere to version control practices (Git, etc.).
*   **Documentation:**  Maintain clear and concise documentation for each module, class, and function.

## 8.  Specific Requirements & Constraints

*   **Data Structures:** Define and document data structures using clear and efficient methods.
*   **Algorithms:** Utilize established algorithms for performance-critical tasks.
*   **Error Handling:** Implement robust error handling mechanisms to prevent crashes and provide informative error messages.
*   **Logging:**  Use structured logging to facilitate debugging and monitoring.
*   **API Definition:** Clearly define the API (Application Programming Interface) for each module and component.

## 9.  Additional Notes

*   The code should be easily understandable by other developers.
*   Prioritize maintainability.
*   Adhere to coding best practices outlined in [[Link to Best Practices Document]]

## 10.  Project-Specific Considerations (Illustrative - Adapt to Actual AGENTS.md)**

*   [Specific task 1] - [Code]
*   [Specific task 2] - [Code]
*   [Specific task 3] - [Code]
```