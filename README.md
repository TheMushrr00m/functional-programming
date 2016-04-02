# A Taste of Functional Programming
Material to introduce functional programming using the Elixir language

## Objectives
* Exposure to functional concepts
* Use functional parts of your existing language of choice you’ve never used before
* Lead you to pursue a functional language more in-depth

## Paradigm evolution
* Mathetmatics (lambda calculus)
* Computer science
* spawn of languages and paradigms
  * functional, procedural, imperative, declarative, object-oriented programming (OOP)
* OOP overload...

## OOP limitations
```
[W]e’re going to be living in a multicore, distributed, concurrent — all the buzz words — world. 
The conventional models we’ve been doing, the OO stuff… is not going to survive in that kind of environment.” - Dave Thomas
```
```
“OOP promised a cure for the scourge of software complexity. …its weaknesses have become increasingly apparent. 
Spreading state all over the place leads to concurrency issues and unpredictable side effects.” - Dave Thomas
```
## Think in Functions not Objects
* Functions
  * Easy to reason about
  * reliable
  * pure
* Data transformation
  * ie. Unix pipes - `cat foo.log | grep bar | wc -l`
* No side-effects
  * Side effects are:
    * modifying state
    * has observable interaction with external functions
* Immutability
  * Immutable data is known data
  * Data that is created is not changed
  * Copy and alter
    * Compilers can perform optimizations because of this
    * Garbage collectors are smart about this
  * Avoid race conditions
* Higher-order functions
  * Functions can receive functions as arguments and return functions
* Where is my *for* loop?
  * map, reduct, filter, reject, take, etc.

## Some (impure and pure) Functional languages
* LISP
* Scheme
* Clojure
* Erlang
* Scala
* OCaml
* Haskell
* F#
* Elm
* Elixir
 
# Elixir
```
“Elixir is a dynamic, functional language designed for building scalable and maintainable applications.
Elixir leverages the Erlang VM, known for running low-latency, distributed and fault-tolerant systems, 
while also being successfully used in web development and the embedded software domain.” - http://elixir-lang.org
```

## Code Examples


# Sources
* http://nerd.kelseyinnis.com/blog/2012/12/17/slides-from-learning-functional-programming-without-growing-a-neckbeard/
* http://reactivex.io/learnrx/
* https://medium.com/@jugoncalves/functional-programming-should-be-your-1-priority-for-2015-47dd4641d6b9#.dzkjdoldo
* http://blog.jenkster.com/2015/12/what-is-functional-programming.html
* http://blog.jenkster.com/2015/12/which-programming-languages-are-functional.html
* https://devchat.tv/react-native-radio/20-CycleJS-Cycle-Native-and-RXJS-with-Andre-Staltz
* https://en.m.wikipedia.org/wiki/Functional_programming
* http://www.vasinov.com/blog/16-months-of-functional-programming/
* http://phuu.net/2014/08/31/csp-and-transducers.html
* https://medium.com/@cameronp/functional-programming-is-not-weird-you-just-need-some-new-patterns-7a9bf9dc2f77#.dmx784uc7
* http://www.elmbark.com/2016/03/16/mainstream-elm-user-focused-design
* https://github.com/hemanth/functional-programming-jargon
* http://www.infoq.com/presentations/functional-declarative-style
* http://michaelfeathers.typepad.com/michael_feathers_blog/2012/03/tell-above-and-ask-below-hybridizing-oo-and-functional-design.html