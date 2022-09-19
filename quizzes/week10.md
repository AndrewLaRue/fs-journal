# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
to provide a reference for locating likes things by giving them the same "space" to occupy
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
 Struct are value types whereas Classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
  // Not sure where #4 is
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
restricted class that cannot be used to create objects (to access it, it must be inherited from another class).
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
 used to modify a method, property, indexer, or event declared in the base class and allow it to be overridden in the derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, protected, internal, and two combinations: protected-internal and private-protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The code is only accessible within the same class
```