# Using Jest

###### This repository is for study only, so I'm basically having fun with a simple example about Jest to understand properly how it works

# 1. Installing Jest 

Let's say you already have a folder called "JS" and inside this folder you have three js files. Open folder "JS" on VSCode (I'm using it, but you can use the one you like).
After that, open the terminal and type `npm init -y` and then, `yarn add jest --dev`. 
Jest dependency will be added to `package.json`. Open it and simplify your life by editing as below:

```
"scripts": {
    "test": "jest"
  }, 
  ```
  
# 2. Creating test files

For example, you have this javascript file called sum.js. To create a test for it, create a new file called sum.test.js. Do it to the other files you need to test: just add "test" before .js.

# 3. Testing

For testing purposes, run `npm test` and it will run all tests.

# 4. Creating reports

If you need a full report, open your package.json and add --coverage :

```
  "scripts": {
    "test": "jest --coverage"
  },
  ```
  
It'll create a new folder called `coverage`. Open it and search for "index.html" and open it on your browser. It will show which code is not being tested.

## And have fun!
