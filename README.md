# Como aplicar SOLID Principles

> Entidade: classe que implementa funções ou Função.

## S: Single Responsibility Principle (SRP)

- A entidade faz mais de alguma coisa semanticamente?
  - Se sim: Refatore.

## O: Open/Closed Principle (OCP)

- Existem outros casos que a entidade pode ser aplicada?
  - Se sim: essa entidade é implementada de um jeito que se aplica para todos os tipos de casos e possíveis futuros casos?
    - Se não: Refatore.

## L: Liskov Substitution Principle (LSP)

- Essa classe terá filhos?
  - Se sim: os filhos e pais dessa classe podem ser utilizados de forma que o utilizador precise saber se é filho ou pai?
    - Se não: Refatore.

## I: Interface Segregation Principle (ISP)

- Essa classe possui interfaces com métodos que não precisam ser implementados necessariamente?
  - Se sim: Refatore.
- Essa função tem parâmetros que não são necessários o tempo todo?
  - Se sim: É possível omitir esses parâmetros?
    - Se não: Refatore.

## D: Dependency Inversion Principle (DIP)

- Essa entidade depende de outra entidade para existir?
  - Se sim: Refatore.
