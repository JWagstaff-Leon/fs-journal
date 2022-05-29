# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To prevent naming collisions
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are reference type while structs are value type. Strcuts also cannot inherit or be inherited, meaning they also cannot be abstract.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The constrcutor
```
## Example 1
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
The return type of the Start method
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Instantiating an instance of the Car class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Allowing inheriting classes to redefine the Start() function
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
internal
protected
private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the same relevant class
```