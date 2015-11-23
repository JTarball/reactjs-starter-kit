## Redux 

### Main Points

 - **A Redux application's state tree is an immutable data structure.**
 That means that once you have a state tree, it will never change as long as it exists. It will keep holding the same state forever. How you then go to the next state is by producing another state tree that reflects the changes you wanted to make.


 To get acquainted with the idea of immutability, it may be helpful to first talk about the simplest possible data structure: What if you had a "counter" application whose state was nothing but a single number? The state would go from 0 to 1 to 2 to 3, etc.

We are already used to thinking of numbers as immutable data. When the counter increments, we don't mutate a number. It would in fact be impossible as there are no "setters" on numbers. You can't say 42.setValue(43).