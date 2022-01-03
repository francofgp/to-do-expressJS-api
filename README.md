# ExpressJS to-do API
### **What is this API about?**

<br>
This is an API where you can do the following:
<br>

-   Log in.
-   Sign up.
-   Create task
-   Read Task
-   Update Task
-   Delete Task
-   Upload an image
-   And more...

It also comes with JWT authentication, and it uses SendGrid to send email when you signup or delete your account.

Some of the endpoint are tested with the **Jest** library.
 
<div align="center">

![Imgur](https://codemoto.io/wp-content/themes/cloudhost/library/images/node-express-mongo.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)

</div>




## [Execute in your editor](#Execute-in-your-editor)

---
Before run the API, you should have installed MongoDB in your computer, and configured the following files:

- *dev.env*
- *test.env*

Feel free to modify these files with you config or use the default.


```bash
PORT=3000
SENDGRID_API_KEY=MySecretApiKey
MONGODB_URL=mongodb://127.0.0.1:27017/todo
JWT_SECRET=secretkey
```

``Attention``: You should use your own **SENDGRID_API_KEY**, by default all the functions that use the SendGrid API are commented, that way you will not have any error if you don't have the private key 😉.

### [Run the project](#Run-the-project)
---

Use [NPM](https://docs.conda.io/projects/conda/en/latest/commands/install.html) to run the project:

```bash
npm install
npm run start
```

You can also run it using nodemon:

```bash
npm run dev
```



## [Run all the tests](#Run-all-the-tests)
---

To run all the tests with Jest, use the following command:
<br>

![Jest](https://camo.githubusercontent.com/ec4626e44870f03423673ea299ceb6f37afa7f9bf848ca5ad095feca41f230b6/68747470733a2f2f6c616e64696e672d706167652d626f6f6b2e66726f6e7431302e636f6d2f696d616765732f6672616d65776f726b732f6a6573742e706e67)

```bash
npm run test
```

## [Example using Postman](#Run-all-the-tests)
---
Here you can use examples of use, using Postman
<br>

**New User**
![new user](/postman/new%20user.png)

**Login**
![login](/postman/login.png)

**Update Profile**
![update profile](/postman/update.png)

**Create task**
![Create task](/postman/new%20task.png)

**Get all task**
![Get all task](/postman/get%20all%20tasks.png)

**and more...**

```bash
npm run test
```

### [Acknowledgements](#Acknowledgements)

---

-   [ExpressJS](https://expressjs.com/) Fast, unopinionated, minimalist web framework for Node.js.
-   [Jest](https://jestjs.io/) a delightful JavaScript Testing Framework with a focus on simplicity.
-   [Moongose](https://mongoosejs.com/) elegant mongodb object modeling for node.js.
-   [Sharp](https://sharp.pixelplumbing.com/) High performance Node.js image processing.
-   [Validator](https://github.com/validatorjs/validator.js) A library of string validators and sanitizers.
-   [JsonWebToken](https://github.com/auth0/node-jsonwebtoken) JsonWebToken implementation for node.js.
-   [Bcryptjs](https://github.com/dcodeIO/bcrypt.js) Optimized bcrypt in plain JavaScript with zero dependencies.
-   [Multer](https://github.com/expressjs/multer)  Middleware for handling "multipart/form-data".
-   [Nodemon](https://github.com/remy/nodemon) Monitor for any changes in your node.js application and automatically restart the server - perfect for development.

### [License](#license)

Closures is provided under the [MIT License](https://github.com/vhesener/Closures/blob/master/LICENSE).

```text
MIT License

Copyright (c) 2022 Pértile Franco Giuliano

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

[MIT](https://choosealicense.com/licenses/mit/)
