#### Goals:

-   Go through a typical TypeScript workflow.
-   Make a network request with `axios` to fetch some fake JSON data from a public API: https://jsonplaceholder.typicode.com, and print the result.

#### The TypeScript Type System

-   TypeScript = JavaScript + A type system
-   Helps us catch errors _during_ development.
-   Uses 'type annotations' to analyze our code.
-   Only active _during_ development.
-   Doesn't provide any performance optimization.

#### Settiung up the TypeScript Compiler

    npm install -g typescript ts-node

#### Compile TypeScript into JavaScript and run it with Node
    tsc index.ts
    node index.js

#### Automatically compile a TypeScript file and run it with Node
    ts-node index.ts
