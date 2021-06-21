# Alexander Gutev

I'm an open source software developer who's authored a number of
project which have seen moderate usage:

# Key Projects

## Common Lisp Utilities

Common Lisp is my go to language for experimenting with new
ideas. I've written a number of utilities which are mostly aimed at
enhancing the language and rectifying its deficiencies.

- [**generic-cl**](https://github.com/alex-gutev/generic-cl)

  A library which provides a generic function interface to functions
  in the Common Lisp standard, allowing them to be extended to
  user-defined classes. This includes comparison functions, arithmetic
  functions and sequence operations.

- [**static-dispatch**](https://github.com/alex-gutev/static-dispatch)

  A library which allows methods of Common Lisp generic functions to
  be chosen at compile-time (based on compile-time type declarations)
  rather than at runtime.

  This library is used by **generic-cl** in order for the generic
  function interface to be close to the same speed as the non-generic,
  and non-extensible, functions in the standard.

- [**cl-environments**](https://github.com/alex-gutev/cl-environments)

  Portability library which provides the [CLTL2 Environment Access
  API](https://www.cs.cmu.edu/Groups/AI/html/cltl/clm/node102.html),
  for retrieving information about variables, functions and
  declarations from environment objects, on all implementations.

- [**cl-form-types**](https://github.com/alex-gutev/cl-form-types)

  A library for determining the return value types of Common Lisp
  forms, based on information contained in the syntactic environment.

## Applications

- [**NuCommander**](/nucommander-gtk) - A fast small orthodox file
  manager.

  _Still a work in progress, however the first release is coming
  soon._

## Programming Languages

- [**Tridash**](http://github.com/alex-gutev/tridash) - A programming
  language based on bindings.

  Releases available however the documentation and tutorials are still
  a work in progress.


