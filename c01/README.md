### Chapter 01: Building, Running, and the REPL

> In this chapter, you’ll invest a small amount
  of time up front to get familiar with a quick,
  foolproof way to build and run Clojure programs.
  It feels great to get a real program running.
  Reaching that milestone frees you up to experiment,
  share your work, and gloat to your colleagues who are
  still using last decade’s languages. This will help keep
  you motivated!

1. #### first things first: what Is Clojure?

    + Clojure was forged in a mythic volcano by Rich Hickey. Using an alloy of
      Lisp, functional programming, and a lock of his own epic hair, he crafted
      a language that’s delightful yet powerful.
    
    + Its Lisp heritage gives you the power to write code more expressively than 
      is possible in most non-Lisp languages, and its distinct take on functional
      programming will sharpen your thinking as a programmer. Plus, Clojure gives
      you better tools for tackling complex domains (like concurrent programming)
      that are traditionally known to drive developers into years of therapy.
      
    + Clojure is a hosted language. Clojure programs are executed within a JVM and
      rely on the JVM for core features like threading and garbage collection.
      Clojure also targets JavaScript and the Microsoft Common Language Runtime
      (CLR), but this book only focuses on the JVM implementation.

2. #### [leiningen](https://leiningen.org/)

    > These days, most Clojurists use Leiningen to build and manage their projects.

    ##### Creating a New Clojure Project
    
        lein new app clojure-noob
 
    ##### Running the Clojure project
    
        lein run
 
    ##### Building the Clojure project
    
        lein uberjar
 
    ##### Using the REPL
        
        lein repl


