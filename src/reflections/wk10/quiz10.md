# C# Fundamentals


**1.** What is the purpose of a `namespace`?

A namespace organizes code and lets it be called in a using statement.

**2.** What is the difference between a `class` and a `struct`?

A class can have methods defined in it that are called in other places.

**3.** What is the method that returns an instance of a class, yet it has no return type?

A void method

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

public

**6.** In the example what is `string` an indication of?

the returned value is a string.

**7.** In the example what is `abstract` preventing?

It is preventing a no return error.

**8.** In the example what is the purpose of `virtual`?

It means it will be attached to something.

**9.** Name four access modifiers:

public, private, internal, protected

**10.** If you set a class or method to private, what can access it?


Only other methods in the class.