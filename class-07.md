# Domain Modeling
> Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. 

## Define a constructor and initialize properties
> To define the same properties between many objects, you'll want to use a constructor function.

`object-oriented programming in JavaScript at its most fundamental level.`

- The new keyword instantiates (i.e. creates) an object.
- The constructor function initializes properties inside that object using the this variable.
- The object is stored in a variable for later use.

## Generate random numbers
- To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.

* Here's some tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.

## Tables:
* What's a Table?
> A table represents information in a grid format. 

`The <table> element is used to add tables to a web page.`
`A table is drawn out row by row. Each row is created with the <tr> element.`
`Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).`
`We can make cells of a table span more than one row or column using the rowspan and colspan attributes.`
`For long tables we can split the table into a <thead>, <tbody>, and <tfoot>.`


# Function, Method. And Object

### BROWSER OBJECT MODEL 
> The Browser Object Model contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen. 

### DOCUMENT OBJECT MODEL 
> The Document Object Model uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page. 

### GLOBAL JAVASCRIPT OBJECTS 
> The global JavaScript objects represent things that the JavaScript language needs to create a model of. For example, there is an object that deals only with dates and times. 

`An object is a series of variables and functions that represent something from the world around us.`

- In an object, variables are known as properties of the object; functions are known as methods of the object.
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
- Arrays and objects can be used to create complex data sets (and both can contain the other). 

