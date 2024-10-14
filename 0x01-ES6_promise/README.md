# 0x01. ES6 Promises 🛠️

Welcome to the **ES6 Promises** project, part of the ALX Backend JavaScript curriculum. In this project, you will explore **Promises** and their usage in JavaScript, focusing on async programming and error handling with async/await.

## 📝 Learning Objectives

By completing this project, you will:

- 🔄 **Understand Promises:** Learn how, why, and when to use promises in JavaScript.
- ⚙️ **Use `.then()`, `.catch()`, and `.finally()`:** Understand how to handle promises using chaining methods.
- 💡 **Implement Async/Await:** Use the `async` and `await` syntax to handle asynchronous tasks more elegantly.
- 🧰 **Error Handling:** Learn how to manage errors using `throw` and `try/catch` with async code.

## 📂 Project Structure

This project includes the following:

1. **Task 0: Keep Every Promise You Make**  
   - **File:** [0-promise.js](./0-promise.js)  
   - **Description:** Return a Promise using the prototype function `getResponseFromAPI()`. Verify if it returns a promise.

2. **Task 1: Don't Make a Promise If You Can't Keep It**  
   - **File:** [1-promise.js](./1-promise.js)  
   - **Description:** Return a Promise in the function `getFullResponseFromAPI(success)`. If the argument is `true`, resolve it with `{ status: 200, body: 'Success' }`, otherwise reject with an error.

3. **Task 2: Catch Me If You Can!**  
   - **File:** [2-then.js](./2-then.js)  
   - **Description:** Handle a Promise resolution and rejection by logging a success message and managing errors with an empty `Error` object.

4. **Task 3: Handle Multiple Successful Promises**  
   - **File:** [3-all.js](./3-all.js)  
   - **Description:** Resolve all promises from `uploadPhoto` and `createUser`, then log the response in a structured format.

5. **Task 4: Simple Promise**  
   - **File:** [4-user-promise.js](./4-user-promise.js)  
   - **Description:** Return a resolved Promise that contains an object with the `firstName` and `lastName` of a user.

6. **Task 5: Reject the Promises**  
   - **File:** [5-photo-reject.js](./5-photo-reject.js)  
   - **Description:** Write a function that returns a rejected Promise with an error message stating that the file cannot be processed.

7. **Task 6: Handle Multiple Promises**  
   - **File:** [6-final-user.js](./6-final-user.js)  
   - **Description:** Combine `signUpUser` and `uploadPhoto` functions and return a list of their results using `Promise.allSettled`.

8. **Task 7: Load Balancer**  
   - **File:** [7-load_balancer.js](./7-load_balancer.js)  
   - **Description:** Write a function that returns the value of the promise that resolves first using `Promise.race`.

9. **Task 8: Throw Error / Try Catch**  
   - **File:** [8-try.js](./8-try.js)  
   - **Description:** Write a function that throws an error if the denominator is `0` and returns the division of two numbers otherwise.

10. **Task 9: Throw an Error**  
    - **File:** [9-try.js](./9-try.js)  
    - **Description:** Write a function `guardrail` that appends the return value or error message of another function to a queue, followed by "Guardrail was processed."

11. **Task 10: Await / Async**  
    - **File:** [100-await.js](./100-await.js)  
    - **Description:** Write an async function that calls `uploadPhoto` and `createUser`, returning an object with their results or an empty object on failure.

## 📚 Resources

### Read or Watch:

- 📘 [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- 📚 [JavaScript Promise: An Introduction](https://developers.google.com/web/fundamentals/primers/promises)
- ⏳ [Await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
- 🎛️ [Async](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- ⚠️ [Throw / Try](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)

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
     cd alx-backend-javascript/0x01-ES6_promise
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

