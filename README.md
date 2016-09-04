### Modern Express | Easy starter project for writing modern Express Applications using TypeScript

This project is used to quickly get started with TypeScript using Express. The intention of this project is to learn to use TypeScript with out getting bogged down in the details of installing and creating a build script. Below is a list of the outcomes of this project.

1. Automates the task of configuring Express
2. Cleanly installs and setups TypeScript with out polluting the global system scope
3. Creates basic Express project to write ES6 or TypeScript code
4. Cleanly builds ES6 or TypeScript code into a build directory
5. Stores and Saves Typings for VSCode
6. Uses `ejs` templates that can be exchanged

**Setup**
---
**[Clone this Repository](https://github.com/jsecademy/modern-express/archive/master.zip)**

```
npm install
```

**Run Builds**
---
```
npm run build
```

**Run Tests**
---
```
npm run test
```

**Run Application**
---
```
npm start
```

**Getting started with this module**
---
Simply start with writing your code in the `server` directory.

```
├── app.ts
├── bin
│   └── www.ts
├── client
├── config
│   └── build.js
├── package.json
├── README.md
├── server
│   ├── routes.ts
│   └── views
│       ├── error.ejs
│       └── index.ejs
├── tsconfig.json
└── typings.json
```

*This module was made possible thanks to [LearnMEAN.com](https://www.learnmean.com/)*
