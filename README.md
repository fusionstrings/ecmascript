# ComeOn! ECMAScript

- http://www.ecma-international.org/ecma-262/6.0/

Idea is to ignite a discussion and reach to a consensus on direction, moving towards goal of adopting native Javascript / ECMA Script modules. ECMA Script modules has been introduced in latest edition of Javascript (officially named ECMA Script 2015), released on June 15, 2015. http://www.ecma-international.org/ecma-262/6.0/index.html#sec-modules.

Since of course no browser natively supports modules yet, Some build process / transpilation is required. Together we will try to explore few of available options and it's feasibility.

Following article might serve as a very good primer to make an informant decesion.

 - https://addyosmani.com/writing-modular-js/

## Upgrading to ECMA Script

Although modules are a very good start towards adoption of ES6. Modularization solves a very fundamental problems which other programming languages had already solved long ago. Of course ECMAScript 2016, commonly known as ES6 brings a lot more on table than just modules.

- https://github.com/lukehoban/es6features
- https://github.com/airbnb/javascript
- https://babeljs.io/docs/learn-es2015/

## Implementation

- https://kangax.github.io/compat-table/es6/

# Few stats
- Signs are encouraging, we can see 90%+ compatibility but's clear no browser / environment fully supports ES6. 
- At same time who got to support 100% implementation across board, even among evergreen browsers?
- There will be incremental releases in future for ECMAScript. Any stage-4 feature on or before final annual release is automatically qualified as standard.
- Implementations might always lag
- Transpilation is the way forward

## Tooling for ECMA Script modules

### Transpilation
- So far Babel is champion
- Typescript is leading in parallel niche (where types are adored) 

### REPL

- https://babeljs.io/repl/
- http://lebab.io/try-it


### Modules loaders

- Webpack
- JSPM
- Babel
- Rollup 

 http://webpack.github.io/docs/comparison.html
