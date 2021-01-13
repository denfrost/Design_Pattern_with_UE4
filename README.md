# Design_Pattern_with_UE4
Use UE4 blueprint to implement design pattern prototype
Unreal Engine 4.25.3

***

## Index

* [x] 01 Simple Factory (Creational pattern)
* [x] 02 Strategy (Behavioral pattern)
* [x] 03 Decorator (Structural pattern)
* [x] 04 Proxy (Structural pattern)
* [x] 05 Factory Method (Creational pattern)
* [x] 06 Prototype (Creational pattern)
* [x] 07 TemplateMethod (Behavioral pattern)
* [x] 08 Facade (Structural pattern)
* [x] 09 Builder (Creational pattern)
* [x] 10_1 Observer(interface)
* [ ] 10_2 Observer(delegate)
* [x] 11 AbstractFactory
* [X] 12 State (Behavioral pattern)
* [x] 13 Adapter
* [x] 14 Memento
* [x] 15 Composite
* [x] 16 Iterator
* [ ] 17 Singleton
* [x] 18 Implementor
* [x] 19 Command
* [x] 20 ChainOfResponsibility
* [x] 21 Mediator
* [x] 22 Flyweight (Structural pattern)
* [x] 23 Interpreter
* [x] 24 Visitor (Behavioral pattern)

+ Another candidate Patterns?
- [ ] Entity-Component-System

- (Sequencing Patterns)
- [ ] Double Buffer
- [ ] Game Loop
- [ ] Update Method

- (Behavioral Patterns)
- [ ] Bytecode
- [ ] Subclass Sandbox
- [ ] Type Object

- (Decoupling Patterns)
- [ ] Component
- [ ] Event Queue
- [ ] Service Locator

- (Optimization Patterns)
- [ ] Data Locality
- [ ] Dirty Flag
- [ ] Object Pool
- [ ] Spatial Partition

***
## Proxy Mode-Adapter Mode-Appearance Mode-Mediator Mode

* The proxy mode mainly considers access to a class while doing some control
* Adapter mode mainly considers the problem of changing the interface of the object
* The appearance mode mainly considers enhanced functions and provides high-level interfaces
* The intermediary pattern group needs to handle the communication between different classes
  

## Decorator Pattern-Chain of Responsibility Pattern
* Decorator mode can replace inheritance and solve inheritance explosion. This is achieved by first calling the parent class method in the interface, and then calling its own method
* The parent class method of the decorator pattern is implemented by the passed-in subclass instance, so the combination of brother methods (decoration) can be realized
* Responsibility chain mode shares responsibilities (functions) by selectively executing parent methods
* The parent class method of the responsibility chain mode is implemented by the passed in subclass instance, so the responsibility link between brothers can be realized

## Builder-Factory
* The builder solves the creation of complex classes and pays attention to the order of parts assembly

## Command Mode-State Mode
* Can be used to eliminate if...else





