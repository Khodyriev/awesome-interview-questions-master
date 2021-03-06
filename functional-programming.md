## Functional programming

### Books

1. [Sicp](https://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs)
2. [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) (free)
3. [Mostly adequate guide](https://github.com/MostlyAdequate/mostly-adequate-guide) (free)
### FP checklist

* What is arity? How to get function arity in JS?
* What is first-class citizen? What is it in JS?
* What are the consequences of the fact that in JS functions are also first-class citizen?
* What is a higher order function?
* Control flow
    - What?
    - How does it affect code complexity?
    - What are the features of control flow in programs written in a functional paradigm?
* Partial use of functions and currying
    - When can partial application of functions be useful?
    - When can currying be useful?
    - What are their differences?
    - What is their influence on the arity of functions?
* Function Composition
    - What?
    - What is it used for?
    - What is a `pipe`?
    - How to implement the `compose` function?
* Point-free style
    - What?
    - What advantages can give?
    - What could be the disadvantages?
* What are side effects? How are they harmful and how are they useful?
* What are pure functions? What are dirty functions? What are the advantages of some over others?
* Can a dirty call come from a pure function? If so, what does it mean?
* How to limit the effect of "dirty functions" on the system?
* What is idempotency? What is the difference between software and mathematical idempotency?
* What is link transparency? Is referential transparency of a function call expression a sufficient sign of the purity of this function?
* Immutability
    - What?
    - Are objects contained in variables declared with `const` immutable?
    - What are the advantages of immune data structures?
    - What is structural sharing and what problems does it solve?
* Recursion
    - What?
    - What are the advantages and disadvantages of the application?
    - What is tail call optimization? Is it supported in JS?
* Study the book [Professor Frisby's Mostly Adequate Guide to Functional Programming] (https://github.com/MostlyAdequate/mostly-adequate-guide) by Franklin Frisby (chapters 8-12 included).
    - [Translation] (https://github.com/MostlyAdequate/mostly-adequate-guide-ru)
* Explore the book [Functional-Light JavaScript] (https://github.com/getify/Functional-Light-JS) by Kyle Simpson (chapters 9-11, plus additions).
* How to implement the functionality of objects through closures and vice versa? What are the advantages of each method?
* How can I create private values ??????in a function? How can they be made immune?
* What are categories? What are morphisms?
* What is isomorphism?
* What is a functor?
* How can I avoid unnecessary passes through the array?
* What is lazy computing? What are the advantages and disadvantages of lazy computing?
* What is transduction? What problems can be solved with this tool?
* What is a pointed functor?
* What are monads? What are they used for? What do the monads below do?
    - `Maybe`
    - `Either`
    - `IO`
* What is associativity?
* What is an applicative functor? What is the scope of its application?
* What do the following utilities do?
    - `identity`
    - `partial` /` partialRight`
    - `prop`
    - `curry` /` uncurry`
    - `cond`
    - `flatMap` /` chain`
* Immutability and state
    - Can the state of the program be immutable?
    - What is the problem of storing the state of the program?
    - Why does a mutable state make it difficult to comply with the guarantee of invariants throughout the program life cycle?
    - Why does mutability impose additional requirements on the order of functions? How can this be avoided?
    - Describe the following state models. How can they be graded according to the degree of danger?
        - Invisible to the client mutable state
        - Encapsulated mutable state
        - Invisible programmer mutable state
        - Two-phase life cycle
        - A mutable state shared between several processes
        - Lack of mutable state
        - Unencapsulated mutable state
        - Managed mutable state
        - Monotonous variable state

### Links
1. [Functional-Light JavaScript (Kyle Simpson)](https://github.com/getify/Functional-Light-JS)
2. [Robert C Martin - Functional Programming; What? Why? When?](https://www.youtube.com/watch?v=7Zlp9rKHGD4)
3. [Functional architecture: a definition](https://blog.ploeh.dk/2018/11/19/functional-architecture-a-definition/)
4. [Functional architecture - The pits of success - Mark Seemann](https://www.youtube.com/watch?v=US8QG9I1XW0)
5. [Functional architecture is Ports and Adapters](https://blog.ploeh.dk/2016/03/18/functional-architecture-is-ports-and-adapters/)
6. [Functional Programming Design Patterns](https://fsharpforfunandprofit.com/fppatterns/)
7. [What is idempotence?](https://szymonkrajewski.pl/what-is-idempotence/)
8. [Why Functional Programming? The Benefits of Referential Transparency](https://sookocheff.com/post/fp/why-functional-programming/)
9. [??????????????????! ???????????????? ???????????????? ??????????????](https://blog.csssr.ru/2017/10/07/side-effects)
10. [Thirteen ways of looking at a turtle](https://fsharpforfunandprofit.com/posts/13-ways-of-looking-at-a-turtle/)
11. [Embracing Immutable Architecture](https://medium.com/react-weekly/embracing-immutable-architecture-dc04e3f08543)
12. [???????????????????? ??????????????????: ?????????????????? ?? ???????????? ?? ????????](http://fprog.ru/2009/issue1/eugene-kirpichov-fighting-mutable-state/)
13. [Immutable Data Structures and JavaScript](https://jlongster.com/Using-Immutable-Data-Structures-in-JavaScript#Immutable.js)
14. [Mutability Leads to Suffering](https://hackernoon.com/mutability-leads-to-suffering-23671a0def6a)
15. [The discussion thread about mutability](http://lambda-the-ultimate.org/node/724#comment-6580)
