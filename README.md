# Head-First-Design-Patterns
Examples from "Head First Design Patterns" implemented in Python

This repo contains code examples from the book ["Head First Design Patterns"](https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly/dp/0596007124) ported to Python. My main aim was to make them as pythonic as possible.

##### Patterns covered so far:

* Strategy

##### Remarks:

* Strategy - There are several ways to define abstract classes in Python. Apart from the way I've used (raising an error when an unimplemented method is called from a subclass), abstract classes can be created with the [abc](https://docs.python.org/3/library/abc.html) module. There's also an interesting example in [Peter Norvig's IAQ](http://norvig.com/python-iaq.html) where he uses a separate function not only raising the appropriate error but also keeping track of the stack frame.  
