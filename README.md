# Como aplicar SOLID Principles

> Entidade: Classe que implementa funções ou Função.

## S: Single Responsibility Principle (SRP)

- A Entidade faz mais de alguma coisa semanticamente?
  - Se sim: Refatore.

## O: Open/Closed Principle (OCP)

- Existem outros casos que a Entidade pode ser aplicada?
  - Se sim: Essa Entidade é implementada de um jeito que se aplica para todos os tipos de casos e possíveis futuros casos?
    - Se não: Refatore.

## L: Liskov Substitution Principle (LSP)

- Essa Classe terá filhos?
  - Se sim: Os filhos e pais dessa Classe podem ser utilizados de forma que o utilizador precise saber se é filho ou pai?
    - Se não: Refatore.

## I: Interface Segregation Principle (ISP)

- Essa Classe possui interfaces com métodos que não precisam ser implementados necessariamente?
  - Se sim: Refatore.
- Essa Função tem parâmetros que não são necessários o tempo todo?
  - Se sim: É possível omitir esses parâmetros?
    - Se não: Refatore.

## D: Dependency Inversion Principle (DIP)

- Essa Entidade depende de outra Entidade para existir?
  - Se sim: Refatore.
