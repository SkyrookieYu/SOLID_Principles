# Single Responsibility Principle

## Thought Process

What is the responsibility of my class/component/microservice?

If the answer is more than one responsibility, you need to split responsibility(functions) into seperate classes/components/microservices.

## Definition

Every class or module should have responsibility over a single part of functionality provided by the software, and that responsibility should be entirely encapsulated by the class or module.

Everything in the class or module should be related to the single purpose.

## Motivation

* Maintainability
* Loose Coupling
* Flexibility and Extensibility
* Parallel Development
* Testability 


## Without Single Responsibility UML
![Without Responsibility UML](https://github.com/tal95shah/SOLID_Principles/blob/master/SingleResponsibility/images/withoutSingleResponsibility.png "Without Responsibility UML")

#### [C++ Code of without Single Responsibility Principle](https://github.com/tal95shah/SOLID_Principles/blob/master/SingleResponsibility/withoutSingleResponsibility.cpp)<br/>
As you can see, a single interface is handling multiple responsibilities (e.g email, logging, auth).

## With Single Responsibility UML
![With Responsibility UML](https://github.com/tal95shah/SOLID_Principles/blob/master/SingleResponsibility/images/withSingleResponsibility.png "With Responsibility UML")

#### [C++ Code of Single Responsibility Principle](https://github.com/tal95shah/SOLID_Principles/blob/master/SingleResponsibility/withSingleResponsibility.cpp)<br/>

