# How to apply Solid Principles

> Notes:
>
> An _Entity_ is:
>
> - a class which implements methods
> - a function

## S: Single Responsibility Principle (SRP)

- Does the Entity do more of one thing semantically?
  - If so: refactor.

## O: Open/Closed Principle (OCP)

- Are there other cases that the Entity can be applied to?
  - If so: Is this Entity implemented in a way that applies to all kind of cases and possible future cases?
    - If not: refactor.

## L: Liskov Substitution Principle (LSP)

- Will this class be inherited?
  - If so: Can the children and parents of that Class be used in such a way that the user needs to know if it is a child or a father?
    - If not: refactor.

## I: Interface Segregation Principle (ISP)

- Does this Class have interfaces with methods that do not necessarily need to be implemented?
  - If so: refactor.
- Does this Function have parameters that are not needed all the time?
  - If so: Is it possible to omit these parameters?
    - If not: refactor.

## D: Dependency Inversion Principle (DIP)

- Does this Entity depend on another Entity to exist?
  - If so: refactor.
