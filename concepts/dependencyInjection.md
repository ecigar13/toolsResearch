# Dependency Injection

### What is it?
In OOP, we use a lot of inheritance (parent, child relationship). It's nice, but it can't satisfy some usecases:
- Parent variable/methods are private, inaccessible, but child class needs it.
- Preventing classes from being inherited (final class)
- Tightly coupled. Imagined multiple services depends on one single package for a few classes.

Dependency injection is similar to aggregation and composition. Mumbo jumbos aside, it means assigning an new object to another object.

### Pros
- Less restrictive compared to OOP.
- Easier to test. Test individual objects, instead of the whole inheritance chain.
- Less error prone. Code can ignore a missing dependency.
### Cons
- Less secure, but as it turn out, code nowadays are often in private repos. Restrict the function, not the code.
- More redudant code, but this is similar to memory-computational trade-off in dynamic programming


### Compared to similar tools
Closer to functional programming, but still OOP. Just a trade-off between more code redundancy and difficulty in managing the code. 