---
marp: true
theme: Example1-theme
---
# Functional Programming in C#
![bg right:60%](img/title.jpg)

---
# About Functional Programming
- Use of pure functions
- No side effects
- Immutable data structures
- C# is multiparadigm and supports functional programming


![bg right:50% 50%](img/01.jpg)

---
# Benefits of Functional C#
- Code reliability and testability
- Efficient, scalable parallelism
- Expressiveness of code 

![bg right:50% 50%](img/02.jpg)

---
# Functional Features in C#
- LINQ - expressive and concise queries and transformations
- Higher-order functions and composition
- Lambda expressions and anonymous functions

![bg right:50% 50%](img/03.jpg)


---
### Example 1
*Computing sum of the squares with LINQ*
```csharp
    var sumOfSquares = Enumerable.Range(1,5).
        Select(n => n * n).
        Sum();
```
---
### Example 2
*Higher-order function and its usage*
```csharp
public static void RunTwice(Action action) {
    action();
    action()
});

RunTwice(() => 
    Console.Out.WriteLine("Hello World"));
```