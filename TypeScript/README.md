# TypeScript

Project from the `holbertonschool-web_react` repository (directory: `TypeScript`).
It covers the fundamentals of TypeScript: basic types, interfaces, classes, functions, DOM manipulation, generics, namespaces, declaration merging, ambient namespaces and nominal typing.

## Learning Objectives

At the end of this project, you should be able to explain, without the help of Google:

- Basic types in TypeScript
- Interfaces, classes, and functions
- How to work with the DOM and TypeScript
- Generic types
- How to use namespaces
- How to merge declarations
- How to use an ambient namespace to import an external library
- Basic nominal typing with TypeScript

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All files end with a new line
- All files are transpiled on Ubuntu 18.04
- TS scripts are checked with `jest`
- A `README.md` at the root of the project folder is mandatory
- Use the `.ts` extension whenever possible
- The TypeScript compiler must not show any warning or error

## Configuration Files

Each task directory contains:

| File | Purpose |
| --- | --- |
| `package.json` | Dependencies and scripts (`start-dev`, `build`, `test`) |
| `.eslintrc.js` | ESLint configuration using `@typescript-eslint` |
| `tsconfig.json` | TypeScript compiler options (`strict`, `noImplicitAny`, ...) |
| `webpack.config.js` | Webpack build, entry point `./js/main.ts` |

## Installation and Usage

```bash
# Install dependencies (inside a task directory)
npm install

# Start the development server
npm run start-dev

# Build the project (should print "No type errors found")
npm run build

# Run tests
npm test
```

## Tasks

| # | Task | Directory |
| --- | --- | --- |
| 0 | Creating an interface for a student | `task_0` |
| 1 | Let's build a Teacher interface | `task_1` |
| 2 | Extending the Teacher class | `task_2` |
| 3 | Printing teachers | `task_3` |
| 4 | Writing a class | `task_4` |
| 5 | Advanced types Part 1 | `task_5` |
| 6 | Creating functions specific to employees | `task_6` |
| 7 | String literal types | `task_7` |
| 8 | Ambient Namespaces | `task_8` |
| 9 | Namespace & Declaration merging | `task_9` |
| 10 | Brand convention & Nominal typing | `task_10` |

### Task 0 - Creating an interface for a student

- Defines a `Student` interface with `firstName`, `lastName`, `age` (number) and `location`.
- Creates two students, `student1` and `student2`, stored in the `studentsList` array.
- Uses vanilla JavaScript to render a table, adding one row per student containing the first name and the location.
- Files: `task_0/js/main.ts`, `task_0/package.json`, `task_0/.eslintrc.js`, `task_0/tsconfig.json`, `task_0/webpack.config.js`

## Project Structure

```
TypeScript/
├── README.md
├── task_0/
│   ├── js/
│   │   └── main.ts
│   ├── package.json
│   ├── .eslintrc.js
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_1/
│   └── ...
└── ...
```

## Resources

- [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [TypeScript documentation](https://www.typescriptlang.org/docs/)
- [TypeScript DOM manipulation](https://www.typescriptlang.org/docs/handbook/dom-manipulation.html)
- [TypeScript object types](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [TSConfig reference](https://www.typescriptlang.org/tsconfig)

## Author
Rahaf Alabdalh 
ق
