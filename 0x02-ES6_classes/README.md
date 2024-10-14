# 0x02. ES6 Classes 🏫

Welcome to the **ES6 Classes** project, part of the ALX Backend JavaScript curriculum. In this project, you will learn about object-oriented programming using **JavaScript ES6** classes, focusing on inheritance, methods, and metaprogramming techniques.

## 📝 Learning Objectives

By completing this project, you will:

- 📚 **Define a Class:** Learn how to define a class and instantiate objects.
- 🛠️ **Add Methods to a Class:** Understand how to add methods, including getters, setters, and static methods.
- 🏗️ **Extend a Class:** Learn how to extend one class from another and inherit attributes and methods.
- 🔧 **Metaprogramming and Symbols:** Explore advanced topics like symbols and metaprogramming in JavaScript.

## 📂 Project Structure

This project includes the following:

1. **Task 0: You Used to Attend a Place Like This at Some Point**  
   - **File:** [0-classroom.js](./0-classroom.js)  
   - **Description:** Implement a class `ClassRoom` that accepts `maxStudentsSize` as an attribute.

2. **Task 1: Let's Make Some Classrooms**  
   - **File:** [1-make_classrooms.js](./1-make_classrooms.js)  
   - **Description:** Implement a function `initializeRooms` that returns an array of 3 `ClassRoom` objects with specific sizes.

3. **Task 2: A Course, Getters, and Setters**  
   - **File:** [2-hbtn_course.js](./2-hbtn_course.js)  
   - **Description:** Implement a class `HolbertonCourse` with attributes: `name`, `length`, and `students`. Implement getters and setters for each attribute.

4. **Task 3: Methods, Static Methods, Computed Method Names... MONEY**  
   - **File:** [3-currency.js](./3-currency.js)  
   - **Description:** Implement a class `Currency` with attributes `code` and `name`. Add a method `displayFullCurrency()` that returns the currency name and code.

5. **Task 4: Pricing**  
   - **File:** [4-pricing.js](./4-pricing.js)  
   - **Description:** Implement a class `Pricing` with attributes `amount` and `currency`. Add methods to display the full price and a static method to convert prices based on a conversion rate.

6. **Task 5: A Building**  
   - **File:** [5-building.js](./5-building.js)  
   - **Description:** Implement an abstract class `Building` with a `sqft` attribute. Classes extending `Building` must implement the method `evacuationWarningMessage()`.

7. **Task 6: Inheritance**  
   - **File:** [6-sky_high.js](./6-sky_high.js)  
   - **Description:** Implement a class `SkyHighBuilding` that extends `Building`. It adds a `floors` attribute and overrides `evacuationWarningMessage()`.

8. **Task 7: Airport**  
   - **File:** [7-airport.js](./7-airport.js)  
   - **Description:** Implement a class `Airport` with `name` and `code` attributes. The default string description of the class should return the airport code.

9. **Task 8: Primitive - Holberton Class**  
   - **File:** [8-hbtn_class.js](./8-hbtn_class.js)  
   - **Description:** Implement a class `HolbertonClass` with `size` and `location`. The class should return the size when cast to a number and the location when cast to a string.

10. **Task 9: Hoisting**  
    - **File:** [9-hoisting.js](./9-hoisting.js)  
    - **Description:** Fix hoisting issues in a set of class declarations and manage student data for the `HolbertonClass`.

11. **Task 10: Vroom**  
    - **File:** [10-car.js](./10-car.js)  
    - **Description:** Implement a class `Car` with attributes `brand`, `motor`, and `color`. Add a method `cloneCar()` that returns a new object of the same class.

12. **Task 11: EVCar (Advanced)**  
    - **File:** [100-evcar.js](./100-evcar.js)  
    - **Description:** Implement a class `EVCar` that extends `Car`. Modify `cloneCar()` to return an instance of `Car`, not `EVCar`.

## 📚 Resources

### Read or Watch:

- 📘 [Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- ⚙️ [Metaprogramming in JavaScript](https://exploringjs.com/es6/ch_metaprogramming.html)

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
     nodejs -v
     npm -v
     ```

2. **Clone the repository**:
   - Clone this project to your local machine:
     ```bash
     git clone https://github.com/Alogyn/alx-backend-javascript.git
     cd alx-backend-javascript/0x02-ES6_classes
     ```

3. **Install project dependencies**:
   - Install the necessary packages like Jest, Babel, and ESLint:
     ```bash
     npm install
     ```

4. **Running code and testing**:
   - You can run your JavaScript files using Node.js:
     ```bash
     node filename.js
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

## 🧑‍💻 Requirements

- Your code should be verified against **ESLint**.
- All functions must be exported.
- Your code must follow the **JavaScript ES6** style.
- The first line of all your files should be `#!/usr/bin/env node`.
- All your files should be executable.

### Environment:

- All scripts will be interpreted/compiled on **Ubuntu 18.04 LTS** using **NodeJS 12.11.x**.

## 📜 License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.
