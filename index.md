---

---

# Introduction
Learning about the build tools available in Javascript.

## Why?
There is a wide range of tools available and I want to find out more about them. To understand them individually and in combination

## Types of tools

### Preprocessers
Tools that can convert between languages and versions of languages.

* Babel: Used to convert cutting edge Javascript to versions that are more widely supported
* SASS and SCSS: Used for stylesheets. These can have variables, mixins and nested selectors
* Typescript: "A superset of Javascript". Javascript with a tpye system and some other features.

### Type systems
Bringing types to JavaScript. This can validate that information passed within the program is the right type. This could be primitives or developer defined types. This extra information works as additional documentation.

* Typescript
* Flow

### Linters
These can identify bad practices and inconsistencies in code styling.

* JSlint
* JSHint
* ESLint

### Testing
Ways to check that code works as intended and that future changes don't break things.

The types:
* Unit testing
* Integration
* End to end
* User acceptance
* Smoke testing

Libraries:
* Mocha / Chai
* Tape
* Awa

Methodologies
* TDD
* BDD

#### Code coverage
Analysis of how much of the code base has been tested.

### Code formatters
This makes sure all code is presented in the same way. This should prevent opinion based style debates

* Prettier
* ESlint

### Buildtools
A tool that runs the other tools.

* Browserify
* Webpack
* Rollup

### CI
A system that deploys new versions of the code. Dependant on passing automated and code reviews.

* CircleCI
* Travis

### Analysis
Code coverage
Package vulnerabilites

## Non buildtools
Other components that are relevant.

### Web hosting
Places to put the working product.

There are staic solutions that return prebuilt resources

There are servers that return dynamic content from APIs

### Databases
Systems to store structured data.
* SQL
* NoSQL
    * Mongo

### Frameworks
* Vue
* React
* Angular
