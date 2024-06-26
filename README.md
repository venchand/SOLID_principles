# SOLID principles

#### Single Responsibility
#### Open/Close
#### Liskov's Substitution
#### Interface Segregation/ Inversion of Control / Isolation
#### Dependency Inversion / Dependency injection/ Durability

## 1. Single responsibility:
	⁃	any class/function/module (unit-of-code) should have a single, well-defined respobsility
	⁃	any piece of code should have only 1 reason to change
	⁃	if you identify that a piece of code has multiple responsibilities - split the code into multiple units

## 2. Open/Close:
	⁃	Code should be closed for modification, yet, it should remain open for extension!
	⁃	modification: changing existing code
	⁃	you might have to change it for bug fixes
	⁃	but you should not change existing code for changing requirements
	⁃	extension: adding new functionality in the face of changing requirements

## 3. Liskovs Substitution Principle:
```
  - Child classes should not violate expectations set by the parent class
  - Any object of 'class Parent' must be replacable (without issues) by a object of class Child extends Parent
  - Child classes should not be forced to implement behavior that they can't exhibit (don't force all Birds to fly, because some of them can't)
```

## 4. Interface Segregation Principle:
```
  - Keep your interfaces minimal
  - clients of your interfaces should not be forced to implement behavior that they don't need
```

## 5. Dependcy Inversion Principle:
```

   - Code should NEVER depend on Low level implementation details
  - Code should dependend ONLY on high level abstractions
Dependency Injection:

Don't create the dependencies yourself - let your clients supply (inject) dependencies into you (via constructor/function params)
```






