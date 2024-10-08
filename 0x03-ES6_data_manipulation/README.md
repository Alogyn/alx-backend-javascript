# 0x03. ES6 Data Manipulation 📊

Welcome to the **ES6 Data Manipulation** project, part of the ALX Backend JavaScript curriculum. In this project, you'll explore various data structures introduced in ECMAScript 6 (ES6) and learn how to manipulate data using arrays, sets, and maps.

## 📝 Learning Objectives

By completing this project, you will:

- 🔍 **Data Manipulation with Arrays:** Understand how to use `map`, `filter`, and `reduce` methods on arrays to manipulate data.
- 💻 **Typed Arrays:** Learn how to work with typed arrays in JavaScript.
- 📦 **Data Structures:** Explore the Set, Map, and WeakMap data structures, their functionalities, and use cases.

## 📂 Project Structure

This project includes the following:

1. **Task 0: Basic List of Objects**  
   - **File:** [0-get_list_students.js](./0-get_list_students.js)  
   - **Description:** Create a function named `getListStudents` that returns an array of student objects with `id`, `firstName`, and `location`.

2. **Task 1: More Mapping**  
   - **File:** [1-get_list_student_ids.js](./1-get_list_student_ids.js)  
   - **Description:** Create a function `getListStudentIds` that returns an array of student IDs from a list of student objects.

3. **Task 2: Filter**  
   - **File:** [2-get_students_by_loc.js](./2-get_students_by_loc.js)  
   - **Description:** Implement `getStudentsByLocation` to filter students by a specific city.

4. **Task 3: Reduce**  
   - **File:** [3-get_ids_sum.js](./3-get_ids_sum.js)  
   - **Description:** Create `getStudentIdsSum` to return the sum of all student IDs using `reduce`.

5. **Task 4: Combine**  
   - **File:** [4-update_grade_by_city.js](./4-update_grade_by_city.js)  
   - **Description:** Implement `updateStudentGradeByCity` to update student grades for a specific city.

6. **Task 5: Typed Arrays**  
   - **File:** [5-typed_arrays.js](./5-typed_arrays.js)  
   - **Description:** Create `createInt8TypedArray` to return a new ArrayBuffer with an Int8 value at a specified position.

7. **Task 6: Set Data Structure**  
   - **File:** [6-set.js](./6-set.js)  
   - **Description:** Implement `setFromArray` to create a Set from an array.

8. **Task 7: More Set Data Structure**  
   - **File:** [7-has_array_values.js](./7-has_array_values.js)  
   - **Description:** Create `hasValuesFromArray` to check if all elements in an array exist within a set.

9. **Task 8: Clean Set**  
   - **File:** [8-clean_set.js](./8-clean_set.js)  
   - **Description:** Implement `cleanSet` to return a string of set values that start with a specific string.

10. **Task 9: Map Data Structure**  
    - **File:** [9-groceries_list.js](./9-groceries_list.js)  
    - **Description:** Create `groceriesList` that returns a map of groceries with names and quantities.

11. **Task 10: More Map Data Structure**  
    - **File:** [10-update_uniq_items.js](./10-update_uniq_items.js)  
    - **Description:** Implement `updateUniqueItems` to update map quantities where the initial quantity is 1.

12. **Task 11: Weak Link Data Structure**  
    - **File:** [100-weak.js](./100-weak.js)  
    - **Description:** Export an instance of WeakMap and implement `queryAPI` to track endpoint queries.

## 📚 Resources

### Read or Watch:

- 📘 [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- 📚 [Typed Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Typed_arrays)
- 📦 [Set Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
- 📍 [Map Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- 🔗 [WeakMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)

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
     cd alx-backend-javascript/0x03-ES6_data_manipulation
     ```

3. **Install project dependencies**:
   - Install the necessary packages such as Jest for testing, Babel for compiling, and ESLint for linting:
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

## 📜 License

This project is licensed under the terms of the [MIT License](https://www.alxafrica.com/terms-conditions-portal/).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.
