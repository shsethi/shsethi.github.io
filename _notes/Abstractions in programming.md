## abstractions
The most common theme in software is that of - abstractions.

We identify the problem. We design the solution. Then we build an abstraction on top of it.  

These abstraction help us to build on top of the solution without knowing the details.

A really good abstraction becomes a STANDARD.

A simple interface is presented to client  of the abstraction to interact with it.

But it also helps us in another way.
  - Decoupled Innovation :  Improvements can be done in each layer separately without affecting the rest of the models


An abstraction which doesn't hide its details well , becomes leaky .


###  Leaky abstraction

As systems become more complex, software developers must rely upon more abstractions. 

Each abstraction tries to hide complexity, letting a developer write software that "handles" the many variations of modern computing.

However, this law claims that developers of _reliable_ software must learn the abstraction's underlying details anyway.

Because All non-trivial abstractions, to some degree, are leaky.

Which means an abstraction that works most of the time, but when a detail of the underlying complexity cannot be ignored, it leaks.

  
 Thus leaking complexity out of the abstraction back into the software that uses the abstraction.