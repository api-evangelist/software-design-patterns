# Software Design Patterns

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
