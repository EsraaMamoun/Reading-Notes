# Error Handling & Debugging

## THE CONSOLE & DEV TOOLS
- Tools built into the browser that help us hunt for errors, that are found in all modern browsers. 


## ERROR HANDLING & DEBUGGING COMMON PROBLEMS
- Common sources of errors, and how to solve them.

**HANDLING ERRORS**
*How code can deal with potential errors gracefully.*

### EXECUTION CONTEXTS
> The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 

***Every statement in a script lives in one of three execution contexts:***
**GLOBAL CONTEXT**
*Code that is in the script, but not in a function. There is only one global context in any page.*

**FUNCTION CONTEXT**
*Code that is being run within a function. Each function has its own function context.*


**VARIABLE SCOPE**
> The first two execution contexts correspond with the notion of scope

### GLOBAL SCOPE
> If a variable is declared outside a function, it can be used anywhere because it has global scope. If we do not use the var keyword when creating a variable, it is placed in global scope.

### FUNCTION-LEVEL SCOPE
> When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope. 


## SCOPE 
- In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

## ERRORS
- If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 

## ERROR OBJECTS 
- Error objects can help us find where our mistakes are and browsers have tools to help us read them. 


***HOW TO DEAL WITH ERRORS***

* **There are two things we can do with the errors:**
1. DEBUG THE SCRIPT TO FIX ERRORS
> If we come across an error while writing a script (or when someone reports a bug), we will need to debug the code, track down the source of the error, and fix it. 

2. HANDLE ERRORS GRACEFULLY
> We can handle errors gracefully using try, catch, throw, and finally statements. 


` JavaScript has 7 different types of errors. Each creates its own error object, which can tell we its line number and gives a description of the error. `