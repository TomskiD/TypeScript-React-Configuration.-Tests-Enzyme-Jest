# Typescript + React

## Overview

```sh
npm install
npm test
npm start
```
## Structure 

```
my-app
├── tsconfig.json
├── readme.md
├── node_modules
├── package.json
├── .gitignore
├── public
   ├── index.html
└── src
    ├──__tests__
        ├──simpleAppTestComponent.test.tsx
    ├── App.tsx
    ├── index.tsx
    └── setupTests.ts
```

Configuration was set up with `create-react-app`. Installed Jest and Enzyme for unit and components testing. 
`simpleAppTestComponent.test.tsx` contains simple render test to check correctness of testing operation