API Test Runner
=================

This repository contains API tests hosted in https://jsonplaceholder.typicode.com/

*Pre-requisites*: `NodeJs` should be installed in your local machine.


Run API tests locally
================

The location of api test package: https://github.com/jahanescenic/todo_api

Clone the repository: git clone https://github.com/jahanescenic/todo_api.git

From the repository root, Run following command to build npm package:
```
npm ci
```

Finally, you're ready to run some tests.  

```
npm run test
```
The above script is going to create html reports under `newman` directory