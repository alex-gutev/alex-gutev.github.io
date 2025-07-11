# Alexander Gutev

I'm a software software developer who's authored a number of
open source [projects](https://github.com/alex-gutev) that have seen moderate usage:

<iframe src="https://github.com/sponsors/alex-gutev/card" title="Sponsor alex-gutev" height="225" width="600" style="border: 0;"></iframe>

I'm also a researcher in the field of Computer Vision and have made contributions to the following fields:

* Human Action Recognition
* Object Tracking
* Machine Learning for Video

# Key Publications

* A Fused Modality Human Action Recognition System Based on Motion Saliency in RGBD Videos<br/>
  Alexander Gutev, Carl James Debono<br/>
  *AICCONF25, 2025*

* [Motion Saliency Based Human Action Recognition in RGBD Videos](https://ieeexplore.ieee.org/document/10793009)<br/>
  Alexander Gutev, Carl James Debono<br/>
  *ICCP, 2024*

The full list of publications is available on my [IEEEXplore profile](https://ieeexplore.ieee.org/author/37087040722).

# Key Open Source Projects

## Common Lisp Libraries

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

## Live Cells Project

Live Cells is a series of reactive programming libraries for various languages which aim to make reactive programming
simpler and more accessible.

- [**Live Cells**](https://livecell.gutev.dev)

  A reactive programming library for Dart and Flutter aiming to simplify application state management and synchronization.

- [**Live Cells C++**](https://gutev.dev/live_cells_cpp)

  Reactive programming for C++

- [**Live Cells Python**](https://gutev.dev/live_cells_py)

  Reactive programming for Python

