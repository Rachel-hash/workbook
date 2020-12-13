# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var, let, and const are used to declare a variable in JavaScript.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a statment that performs code. You can call a function multiple times anywhere in your project and it will repeat its code. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S.O.L.I.D stands for Single responsibility principle, meaning a class should only have one job. Open-closed principle, meaning that objects should be open to adding new features or components without breaking everything.Liskov substitution principle, meaning that every child class should be substitutable for their parent class. Interface segregation principle, meaning that there should not be extra interfaces/methods that the client does not use. Dependency inversion principle, meaning that high level modules shouldn't depend on low level modules. 
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple's current position is .fruit[2]. I know this because you count items in an array starting with 0. 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them.name, them.hair, them.friends[])
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(potions >= automaticUpgrades.snape.price) {
        automaticUpgrades.snape.quantity++;
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
It is called the iteration, and you would put i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. The file first accessed is source.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The nine ECMAScript types are 1: undefined, 2: boolean, 3: number, 4: string, 5: bigInt, 6: symbol, 7: object, 8: function, and 9: null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is placed inside the () of a function, and an argument is placed inside the {} of a function. Parameters are the names listed in the function definition, so whenever you want to have the code in the function run you can call those parameters. Arguments are the values passed to and received by the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is stored directly in the location that the variable accesses. So primitive values are not global. A reference value is stored in the variable location and is a pointer to a location in memory where the object is stored. THey are objects stored in the heap.
```