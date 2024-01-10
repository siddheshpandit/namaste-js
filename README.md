# namaste-js
# Everything in JS happens inside an execution context

Reference link: https://www.freecodecamp.org/news/how-javascript-works-behind-the-scene-javascript-execution-context/#:~:text=When%20the%20JavaScript%20engine%20scans,for%20the%20variables%20and%20functions.

What is execution context?
Execution context is like an environment that handles entire transformation and execution of the code.
Execution context has two components
1. Memory (Contains Key-Value pair of variables) also know as variable environment.
2. Code (Place where code is executed line by line) also knows as thread of execution.

When you invoke(run) a function a brand new execution context is created.

Javascript is a synchronous single threaded language.
Only execute one line at a time line by line.


