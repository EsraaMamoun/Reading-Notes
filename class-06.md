# Object Literals

## WHAT IS AN OBJECT? 
> Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
> If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has.
> Each individual hotel might have a different name and a different number of rooms.
### FUNCT IONS, METHODS & OBJECTS IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS
> If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. > For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms. 

` The variables and named functions, properties and methods have a name and a value. In an object, that name is called a key. `
`An object cannot have two keys with the same name. This is because keys are used to access their corresponding values.`
`The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function.`


# Document Object Model

`The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.`

> The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

1. MAKING A MODEL OF THE HTML PAGE

- When the browser loads a web page, it creates a model of the page in memory.
- The DOM specifies the way in which the browser should structure this model using a DOM tree.
- The DOM is called an object model because the model (the DOM tree) is made of objects.
- Each object represents a different part of the page loaded in the browser window.


2. DOCUMENT OBJECT MODEL ACCESSING AND CHANGING THE HTML PAGE

- The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
- we will hear people call the DOM an Application Programming Interface (API).
- User interfaces let humans interact with programs; APls let programs (and scripts) talk to each other. The DOM states what our script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user. 