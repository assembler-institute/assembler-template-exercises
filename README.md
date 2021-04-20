`#tag-1` `#tag-2` `#tag-3` `#assembler-school` `#master-in-software-engineering`

# Assembler School: {technologyName} Exercises <!-- omit in toc -->

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

Brief explanation of the purpose of these exercises, which is what they are
going to create, learn, the objective of carrying out these exercises.

You can separate the explanation in different paragraphs, use all the paragraphs
that you need without going overboard.

**Feel free to add any supporting info in the `README` such as images, links,
etc**

**Examples:**

---

> In these exercises you will learn how to build backend apps with Node.js.

> Voluptate excepteur occaecat enim minim tempor. Quis velit aute excepteur
> adipisicing enim excepteur nulla Lorem in cupidatat sint. Lorem non occaecat
> voluptate tempor excepteur. Exercitation ea quis labore nisi dolor labore.
> Exercitation minim officia Lorem excepteur nisi aliqua commodo cupidatat. Et
> officia deserunt nostrud anim.

# Index <!-- omit in toc -->

- [Getting Started](#getting-started)
- [Exercises](#exercises)
- [More examples of defining exercises instructions](#more-examples-of-defining-exercises-instructions)
- [Technologies used](#technologies-used)
- [Project requirements](#project-requirements)
- [Project delivery](#project-delivery)
- [Resources](#resources)

## Getting Started

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

**This section details how the students can clone this repository and install
the required dependencies.**

---

First, you will need to clone the repo:

```bash
$ git clone ...
```

Then, you will have to install all the dependencies with npm:

```bash
$ npm install
```

You will probably have to execute the following command in the terminal line in
order to fix the dependency issues:

```bash
$ npm audit fix
```

\* Here you can add more steps if they are required \*

```bash
...
```

## Exercises

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

**This section details how the students can run the project and execute the
tests. Include all the necessary info and related commands.**

**Here are an example of how you can explain this part to the students:**

---

Once you have completed al the steps of the [Getting Started](#getting-started)
section, you will have to execute the following command that will prepare a
localhost environment.

The command will compile all the necessary assets into a new folder called
[dist](./dist) and it will open a localhost server that allows you to do the
exercises without having to reload the page:

```bash
npm run start
```

Finally you must open a new terminal (you leave the previous one open since it
has the test server running).

In this new terminal you will have to execute the following command, which will
allow you to know in real time if you have correctly implemented the exercises.

```bash
npm run test
```

_Keep in mind that the files to which you must implement your solution are those
found inside the [src](./src) folder_

In case that you want to see in the browser the result of your solutions, you
will have to call to the function of each exercise in the same JS file:

```js
// 01-exercise.js

exercise01();

function exercise01() {
  // Here is your solution
}
```

Now you will be able to see the solution in the browser.

Once you have validated that the solution is applied correctly, you will have to
remove the call that you have made manually to the function so that the test
passes successfully.

```js
// 01-exercise.js

function exercise01() {
  // Here is your solution
}
```

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

## More examples of defining exercises instructions

---

### CRUD API Exercises

In this step we will create the CRUD endpoints for a Book schema that we have
created for you. You will have to create endpoints and controllers so that you
can create, read, modify and delete book resources.

The schema can be found in the `src/models/book-model.js` file.

### Seeding Users and Books

Before you get started, to make sure you have enough data in the database you
can execute the `async seedBooks()` function from the `src/db/seed.js` file.
This will remove all existing users and books and create new ones from scratch.

You can run the `seedBooks()` function in the `index.js` file when starting the
server.

### Tests Suites

The test suites for these exercises can be executed with the following script:
`npm run test:01:crud-api`.

Open the files indicated bellow and read the instructions and requirements of
the tests to solve them.

- Once you are done the instructor will solve each step
- If you get stuck you can find the answers in the
  `01-crud-api-exercises-solution` branch
- Try not to peek at the solutions and solve them with your pair programming
  partner
- To finish this part you have 20 minutes

### 1. Create the books CRUD controllers in the `/src/routes/book-controllers.js` file

### 2. Create the books CRUD routes in the `/src/routes/book-routes.js` file

- **Test suite:** "books crud controllers"

---

### Mongoose Schema Exercises

The test suites for these exercises can be executed with the following script:
`npm run test:01:schemas`.

Open the files indicated bellow and read the instructions and requirements of
the tests to solve them.

- Once you are done the instructor will solve each step
- If you get stuck you can find the answers in the
  `01-mongoose-schema-exercises-solution` branch
- Try not to peek at the solutions and solve them with your pair programming
  partner
- To finish this part you have 20 minutes

### 1. Create the connection logic in the `/src/db/connect.js` file

- **Test suite:** "1. the `connect` function calls `mongoose.connect` with the
  url and options"

### 2. Create the `User` model in the `/src/models/user-model.js` file

- **Test suite:** "2. create the 'User' model following the schema requirements"
- **Test suite:** "3. encrypt the password before storing it in the database"
- **Test suite:** "4. add a 'comparePassword' method to the 'User' schema"

---

## Technologies used

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

**This section details the technologies that are used in the project.**

**Here are some examples of technologies used:**

---

- HTML
- CSS
- JS
- LocalStorage
- ...

## Project requirements

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

This section details the **main requirements** of the project that the student
must take into account when they deliver their solution.

A more **detailed description with all the requirements and steps** that the
students need to complete for the project will be included in the **Google Docs
version of the requirements document.**

**Here are some examples of project requirements:**

---

- You must develop this project using a single HTML page
- You cannot use third-party libraries
- You must use semantic HTML5 elements for all the contents of the application

## Project delivery

To deliver this project you must follow the steps indicated in the document:

- [Submitting a solution](https://www.notion.so/Submitting-a-solution-524dab1a71dd4b96903f26385e24cdb6)

## Resources

---

#### DELETE THIS MESSAGE AND THE TOP AND BOTTOM SEPARATORS IN THE FINAL VERSION OF THIS `README.md`

This section include all the main resources that the students should check for
learning more about the technologies they are using or that might apply to their
project.

**Here are some examples of resources:**

---

- [JavaScript HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)
- [JavaScript Dates](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [LocalStorage](https://developer.mozilla.org/es/docs/Web/API/Window/localStorage)
- [...](...)

## License <!-- omit in toc -->

[MIT](https://choosealicense.com/licenses/mit/)
