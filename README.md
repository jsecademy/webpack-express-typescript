### Modern Express | Easy starter project for writing modern Express Applications using TypeScript and Webpack

This project is used to quickly get started with Webpack using Express and TypeScript. The intention of this project is to learn to use Webpack with out getting bogged down in the details of configuring Webpack. Below is a list of the outcomes of this project.

1. Automates the task of setting up Webpack
2. Cleanly installs and setups Webpack with out polluting the global system scope
3. Creates basic Express project to write TypeScript
4. Cleanly builds TypeScript code into a build directory
5. Stores and Saves Typings for VSCode
6. Uses `ejs` as the templating engine

**Setup**
---
**[Clone this Repository](https://github.com/jsecademy/webpack-express-typescript/archive/master.zip)**

```
npm install
```

**Run Builds**
---
```
npm run build
```

**Run Application**
---
```
npm start
```

**Getting started with this module**
---
Simply start with writing your TypeScript code in the `server` directory

```
├── app.ts
├── bin
│   └── www.ts
├── build
│   └── compiled
├── config
│   └── webpack.config.js
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
