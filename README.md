# Software Design Patterns

Software design patterns are reusable solutions to commonly occurring problems in software design. Originally catalogued by the Gang of Four (GoF) in 1994 in "Design Patterns: Elements of Reusable Object-Oriented Software," they include 23 patterns organized into three categories: Creational (5 patterns), Structural (7 patterns), and Behavioral (11 patterns).

**URL:** [https://raw.githubusercontent.com/api-evangelist/software-design-patterns/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/software-design-patterns/refs/heads/main/apis.yml)

## Tags

- Architecture
- Best Practices
- Object-Oriented Programming
- Software Engineering
- Design Patterns
- Gang of Four
- Creational Patterns
- Structural Patterns
- Behavioral Patterns

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Refactoring.Guru Design Patterns

Refactoring.Guru is a comprehensive catalog of all 23 Gang of Four software design patterns with examples in Java, C#, Python, PHP, TypeScript, Go, and other languages.

**Tags:** Design Patterns, Gang of Four, Refactoring, Best Practices, Object-Oriented Programming

#### Properties

- [Documentation](https://refactoring.guru/design-patterns)
- [Website](https://refactoring.guru/)
- [JSON Schema](json-schema/design-pattern-schema.json)
- [JSON Structure](json-structure/design-pattern-structure.json)

### Patterns.dev

Patterns.dev is a free online resource covering modern design, rendering, and performance patterns for JavaScript and React applications.

**Tags:** JavaScript, React, Web Development, Design Patterns, Performance Patterns

#### Properties

- [Documentation](https://www.patterns.dev/)
- [Website](https://www.patterns.dev/)

## JSON Schema

| Schema | Description |
|---|---|
| [design-pattern-schema.json](json-schema/design-pattern-schema.json) | JSON Schema for documenting a Gang of Four design pattern with intent, structure, and implementation guidance |

## JSON Structure

| Structure | Description |
|---|---|
| [design-pattern-structure.json](json-structure/design-pattern-structure.json) | Structure documentation for DesignPattern and Participant resources, plus category index |

## JSON-LD

| Context | Description |
|---|---|
| [software-design-patterns-context.jsonld](json-ld/software-design-patterns-context.jsonld) | Linked data context mapping Gang of Four pattern concepts to schema.org |

## Examples

| Example | Description |
|---|---|
| [observer-pattern-example.json](examples/observer-pattern-example.json) | Complete documentation of the Observer behavioral pattern |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [software-design-patterns-vocabulary.yml](vocabulary/software-design-patterns-vocabulary.yml) | Comprehensive vocabulary of all 23 Gang of Four patterns plus modern extensions |

## Pattern Catalog

### Creational Patterns (5)
Object creation mechanisms that increase flexibility and reuse:

| Pattern | Intent |
|---|---|
| **Abstract Factory** | Creates families of related objects without specifying concrete classes |
| **Builder** | Separates complex object construction from its representation |
| **Factory Method** | Lets subclasses decide which class to instantiate |
| **Prototype** | Creates new objects by cloning a prototype instance |
| **Singleton** | Ensures a class has only one instance with global access |

### Structural Patterns (7)
Object composition and class relationships:

| Pattern | Intent |
|---|---|
| **Adapter** | Makes incompatible interfaces work together |
| **Bridge** | Decouples abstraction from implementation |
| **Composite** | Composes objects into tree structures for part-whole hierarchies |
| **Decorator** | Attaches additional responsibilities dynamically |
| **Facade** | Provides a simplified interface to a complex subsystem |
| **Flyweight** | Shares fine-grained objects efficiently |
| **Proxy** | Controls access to another object |

### Behavioral Patterns (11)
Object interaction and algorithm encapsulation:

| Pattern | Intent |
|---|---|
| **Chain of Responsibility** | Passes requests along a chain of handlers |
| **Command** | Encapsulates requests as objects for queuing and undo |
| **Interpreter** | Defines grammar and interpreter for a language |
| **Iterator** | Provides sequential access to aggregate elements |
| **Mediator** | Encapsulates how objects interact |
| **Memento** | Captures and restores object state externally |
| **Observer** | Defines one-to-many dependency for state change notification |
| **State** | Alters behavior when internal state changes |
| **Strategy** | Defines interchangeable algorithm family |
| **Template Method** | Defines algorithm skeleton with subclass-defined steps |
| **Visitor** | Defines operations on object structure elements |

## Common Properties

- [Refactoring.Guru Design Patterns](https://refactoring.guru/design-patterns)
- [Patterns.dev](https://www.patterns.dev/)
- [GOFPattern.com](https://www.gofpattern.com/)
- [Spring Framework Guru - GoF Patterns](https://springframework.guru/gang-of-four-design-patterns/)
- [Wikipedia: Design Patterns](https://en.wikipedia.org/wiki/Design_Patterns)
