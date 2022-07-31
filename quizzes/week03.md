# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation
Inheritance
Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
grouping like things together and burying them deeper
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Singe responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint and an instance of the class is what you create with it
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A layer of separation between the user and the appstate; a bodyguard
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
By splitting up a large file into many smaller ones that are composed of specific groups of functions/methods/models/etc.  This makes it easier to find what your looking for.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Acts as a go between for the user and the service, this is the layer you draw things to the page at.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The logical center of a project.  It handles any changes to the DOM and is the only layer that should connect with the appstate.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Blueprints and templates used to build things.
```
