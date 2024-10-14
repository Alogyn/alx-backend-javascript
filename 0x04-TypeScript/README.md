# 0x04. TypeScript 🛠️

Welcome to the **TypeScript** project, part of the ALX Backend JavaScript curriculum. This project will help you learn the basic and advanced features of **TypeScript**, including types, interfaces, classes, and working with the DOM.

## 📝 Learning Objectives

By completing this project, you will:

- 🔧 **Understand Basic Types in TypeScript:** Learn about the types that TypeScript adds on top of JavaScript.
- 📜 **Interfaces and Classes:** Define and work with interfaces and classes in TypeScript.
- 🌐 **DOM Manipulation:** Use TypeScript to interact with and manipulate the DOM.
- 🧩 **Generic Types and Namespaces:** Learn how to work with generic types and namespaces in TypeScript.
- 🔗 **Declaration Merging and Ambient Namespaces:** Understand how to merge declarations and import external libraries using ambient namespaces.

## 📂 Project Structure

This project includes the following:

1. **Task 0: Creating an Interface for a Student**  
   - **File:** [task_0/js/main.ts](./task_0/js/main.ts)  
   - **Description:** Create an interface named `Student` and display a table of students' first names and locations using vanilla JavaScript.

2. **Task 1: Let's Build a Teacher Interface**  
   - **File:** [task_1/js/main.ts](./task_1/js/main.ts)  
   - **Description:** Define an interface for `Teacher` with required and optional properties, and allow dynamic property addition.

3. **Task 2: Extending the Teacher Class**  
   - **File:** [task_1/js/main.ts](./task_1/js/main.ts)  
   - **Description:** Create an interface `Directors` that extends `Teacher`, adding the `numberOfReports` attribute.

4. **Task 3: Printing Teachers**  
   - **File:** [task_1/js/main.ts](./task_1/js/main.ts)  
   - **Description:** Write a function `printTeacher` that returns a formatted string for teacher names.

5. **Task 4: Writing a Class**  
   - **File:** [task_1/js/main.ts](./task_1/js/main.ts)  
   - **Description:** Implement a `StudentClass` with methods for working on homework and displaying the student's name.

6. **Task 5: Advanced Types - Part 1**  
   - **File:** [task_2/js/main.ts](./task_2/js/main.ts)  
   - **Description:** Implement `Director` and `Teacher` classes with specific methods, and create a `createEmployee` function that returns either a `Teacher` or `Director`.

7. **Task 6: Creating Functions Specific to Employees**  
   - **File:** [task_2/js/main.ts](./task_2/js/main.ts)  
   - **Description:** Write functions `isDirector` and `executeWork` that operate differently based on the employee's role.

8. **Task 7: String Literal Types**  
   - **File:** [task_2/js/main.ts](./task_2/js/main.ts)  
   - **Description:** Create a string literal type `Subjects` and a function `teachClass` to print the subject being taught.

9. **Task 8: Ambient Namespaces**  
   - **File:** [task_3/js/main.ts](./task_3/js/main.ts)  
   - **Description:** Define ambient type declarations for the `crud.js` library and implement functions for interacting with database-like objects.

10. **Task 9: Namespace & Declaration Merging**  
    - **File:** [task_4/js/subjects](./task_4/js/subjects)  
    - **Description:** Create a `Subjects` namespace and use declaration merging to extend interfaces for different subjects (Cpp, Java, React).

11. **Task 10: Update task_4/js/main.ts**  
    - **File:** [task_4/js/main.ts](./task_4/js/main.ts)  
    - **Description:** Export constants for different subjects, set a teacher for each, and log their respective requirements and availability.

12. **Task 11: Brand Convention & Nominal Typing**  
    - **File:** [task_5/js/main.ts](./task_5/js/main.ts)  
    - **Description:** Implement `MajorCredits` and `MinorCredits` interfaces with a brand property and write functions to sum these credits.

## 📚 Resources

### Read or Watch:

- 📘 [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- 📚 [TypeScript Documentation](https://www.typescriptlang.org/docs/handbook/basic-types.html)

## ⚙️ Setup Instructions

To get started with this project, follow these steps:

1. **Install Node.js and npm**:
   - To install Node.js (version 12.x), run the following commands:
     ```bash
     curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
     sudo apt-get install -y nodejs
     ```
   - Verify installation:
     ```bash
     node -v
     npm -v
     ```

2. **Clone the repository**:
   - Clone this project to your local machine:
     ```bash
     git clone https://github.com/Alogyn/alx-backend-javascript.git
     cd alx-backend-javascript/0x04-TypeScript
     ```

3. **Install project dependencies**:
   - Install the necessary packages for TypeScript, Webpack, Babel, and Jest:
     ```bash
     npm install
     ```

4. **Running code and testing**:
   - You can run your TypeScript files using the TypeScript compiler or Webpack:
     ```bash
     npm run build
     ```
   - Run all the tests using Jest:
     ```bash
     npm run test
     ```

5. **Linting your code**:
   - To check for any linting issues, run ESLint:
     ```bash
     npm run lint
     ```

## 📜 License

This project is licensed under the terms of the [MIT License](https://www.alxafrica.com/terms-conditions-portal/).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.

