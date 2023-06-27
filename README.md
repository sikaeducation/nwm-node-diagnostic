1.

> Using JavaScript, write a function that accepts two numbers and returns them multiplied together.

2.

> Add the JavaScript code that iterates through each of these numbers using a `for` loop and accumulates their sum into `sum`.

```js
const numbers = [1, 2, 3, 4, 5]
let sum = 0

// Your code here

console.log(sum)
```

3.

> Using `.map()` and `.forEach()`, add the necessary JavaScript to print out each of the words with an `!` appended to the end, such as:

```
One!
Two!
Three!
Four!
Five!
```

```js
const words = [{
  content: "One",
},{
  content: "Two",
},{
  content: "Three",
},{
  content: "Four",
},{
  content: "Five"
}]
```

4.

> Write the Node.js code that imports the `readFile` function from the `fs/promises` module using either ESM or CommonJS syntax. Invoke it with the argument `"README.md"`, which will evaluate to a promise. Print the result of the resolved promise to the console.

5.

> Add appropriate TypeScript types to this tuple:

```ts
const someTuple = [5, "Five", true]
```

6.

> Write a TypeScript function that accepts a string and a number and returns whether the length of the string is greater than the number.

7.

> Write a type for the following object:

```ts
const someObject = {
  someString: "Some value",
  someNumber: 42,
  anotherObject: {
    someBoolean: true,
  },
}
```

8.

> Add the type `User` as a generic to the initial call:

```ts
type User = {
  username: string;
}

database("User")
  .select()
  .first()
  .then(user => {
    console.log(user)
  })
```

9.

> Describe Node as best you can.

10.

> Describe RESTful APIs as best you can.

11.

> Write the shell code to install the npm modules `lodash`, `jest`, and `express`.

12.

> Write the code to respond to any `GET` request to the root of the server with the following JSON:

```json
{
  "message": "Hello, world!"
}
```

```ts
import express from "express"

const app = express()
```

13.

> Add the TypeScript needed to connect to a database at "mysql://localhost:3306". Then, add a route that responds to `POST` requests at `/users` and pulls an object out of the body. Insert the `username` value of the object into the `username` column of the `user` table.

```ts
import express from "express"
import knex from "knex"

const app = express()

const config = {
}

const database = knex()

const PORT = 3000
app.listen(PORT)
```

14.

> Write the Jest code to assert that `getFive` returns `5` when invoked.

```ts
import {test} from "jest"

const getFive = () => 5

test() // Your code here
```

15.

> Write code to assert the basic behavior of the `transformAll` function.

```ts
import {test} from "jest"

const transformAll = (
  numbers: number[],
  transformation: (number: number) => number,
) => transformation(number)

test() // Your code here
```

16.

> Using Supertest and Jest, assert that a request to `/messages/1` returns 200 and return the JSON `{ "message": "Hello, world!"}`:

```ts
import { test } from "jest"
import request from "supertest"
import app from "./app"

// Your code here
```
