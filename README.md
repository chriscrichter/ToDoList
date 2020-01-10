# ToDoList
To Do List Project

# Render Todos

In this activity you will be writing code to render an array of todo items to the list.

## Instructions

* Open the `script.js` file provided to you. You have been provided the necessary variable declarations as well as an array of todo items.

* Your goal is to create a function that will render our todos into a list in the browser.

  * Initially set the text content of the todoList to an empty string.
  
  * todoCountSpan should show the total count of todos on the page.
  
* Inside of your render function you will also need a for loop.

  * It should loop over the `todos` array creating an `li` element for each index of the array.
  
  * It should set the content of the created `li` element to the value of the current array index.
  
  * Finally the new `li` should be appended to the `ul` provided.


Pseudo-Code:

make a header
 - title heading
 
 make a add todo section
  -add a title <h2>
  -input with placeholder
  
Make todo list section
  -add todo count at top
  -show todos that currently exist
  -check local storage for todos
  -build todo list
  -go through existing todos
  -make todo element
  -add text to todo
  -add complete button
  -append it to the page
  -create a new todo-get
    -text (value) from input
    -add it to the todo data
    -re-display existing todos
  -complete a todo (remove it)
    -complete button clicked
    -remove the todo from todo data
    -update the count
    -re-display existing todos
