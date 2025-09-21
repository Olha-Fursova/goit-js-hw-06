# JavaScript Homework 06 (GoIT Neoversity) – OOP and Classes

## Project Overview  
This project is a set of JavaScript exercises from GoIT Neoversity.

The main goal is to practice Object-Oriented Programming (OOP) in JavaScript, including:

- understanding the this keyword in different contexts (global scope, object methods, arrow functions, callbacks)

- using call, apply, and bind methods

- working with classes, instances, interfaces

- applying prototypal inheritance

- creating reusable objects with classes and private properties


**Task 1.** User Account (object methods and this). Refactor the customer object by correctly using this in its methods. Key requirements: getBalance() returns the current balance, getDiscount() and setDiscount(value) manage the discount property, getOrders() returns all orders, addOrder(cost, order) updates balance and adds a new order.

**Task 2.** Storage (class with private property). Create a Storage class for managing product stock. Methods: getItems() — returns an array of items, addItem(newItem) — adds a new item, removeItem(itemToRemove) — removes an item from the list.

**Task 3.** StringBuilder (class with string manipulation). Create a StringBuilder class with private property value. Methods: getValue() — returns the current string, padEnd(str) — adds str to the end, padStart(str) — adds str to the beginning, padBoth(str) — adds str to both sides. 

**Task 4.** Create a function getTotalBalanceByGender(users, gender) that returns the total balance of users whose gender matches the given parameter.

## File Structure  
Each task is implemented in a separate file inside the project folder:  

goit-js-hw-06/ 

├── js/  
│ ├── task-1.js  
│ ├── task-2.js   
│ └── task-3.js  
├── index.html  
├── .gitignore  
├── .prettierrc  
└── README.md  

## How to Run  
1. Clone this repository.  
2. Click on GitHub Pages link in description to this project.  
3. Open the browser console (DevTools → Console) to see the results of function calls.  

## Conclusions

- Practiced working with this, object methods, and context binding.

- Learned how to design and use classes with private properties.

- Implemented inheritance and OOP principles for building structured, reusable code.

- Improved ability to model real-world problems with JavaScript classes.
