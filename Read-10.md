# Error Handling & Debugging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully. 

Each time a script enters a new execution context, there are two phases
of activity: 


- PREPARE
  - The new scope is created
  - Variables, functions, and arguments are created
  - The value of the this keyword is determined

- EXECUTE
  - Now it can assign values to variables
  - Reference functions and run their code
  - Execute statements 

  ![error](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6Ijg4NDgzMDE5ZjVlNGJkZTZhOGE3YTcxM2Q2MGRiZTk5LnBuZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=8041732636e435d842d9e2369e8c9704014c499882461b192fab65421e35d36f)


Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors. 

- DEBUG THE SCRIPT TO FIX ERRORS 
   - `If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it. `

- HANDLE ERRORS GRACEFULLY 
   - `You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.
Sometimes, an error may occur in the script for a
reason beyond your control. For example, you might
request data from a third party, and their server
may not respond. In such cases, it is particularly
important to write error-handling code. `


Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.


  