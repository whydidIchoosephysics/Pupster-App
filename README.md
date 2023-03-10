# Pupster-App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description:

The app creates a `generatedREADME.md` file, and fills in the sections based on the input given by the user in the terminal with the use of Node.js and the Inquirer package. The file is created with the use of the fs package.

An `arrObj` object is created as an array containing all the Inquirer Prompts. An asynchronous function `x()` runs only once all the promts have been answered by the user. The answers are then provided to a Generator function - for the License option, a Switch Statement is used before the value is passed, so the link to the correct badge is linked to it. The generator function calls a function that returns the prototype from which the README file is being created, with the given answers in it.

An `exampleREADME` file is provided, that was created using this script.


[**Video Demo**](https://drive.google.com/file/d/17HAMkaHpc1YM4lG3RBAn2tKEkcR5B8If/view?usp=sharing)

https://user-images.githubusercontent.com/93586814/222556373-733bc248-3607-440e-97ff-59baae45cc72.mp4

## Table of Contents:

**[Installation](#Installation)**<br>
**[Usage](#Usage)**<br>
**[License](#License)**<br>
**[Questions](#Questions)**<br>
  
## Installation:

1. Create React App

```
npx create-react-app "pupster"
```

2. Navigate to the `pupster` folder

```
cd pupster
```

3. Install Axios, React Router & Bootstrap

```
npm install axios react-router-dom bootstrap

```

4. Make sure to import Bootstrap in the `index.js` file

```
import 'bootstrap/dist/css/bootstrap.min.css'
```

## Usage:

In the terminal:

1. Navigate to the correct directory:

```
cd ./pupster
```

2. Start by running

```
npm start
```


## License:

MIT License

## Questions:

For any questions find me on:

- Github: [**@whydidIchoosephysics**](https://github.com/whydidIchoosephysics)