# AbstractFactoryPatternBasic

# Vehicle Factory Design Pattern in Python

This repository demonstrates the implementation of the **Abstract Factory** design pattern in Python, specifically used for creating different types of vehicle objects (e.g., Honda, Toyota, and BMW). The code defines an interface for the vehicles and their concrete implementations, as well as an abstract factory to instantiate them.

## Design Pattern Overview

### Abstract Factory
The **Abstract Factory** pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes. In this example, the factories (`HondaFactory`, `ToyotaFactory`, `BMWFactory`) create corresponding car objects (`Honda`, `Toyota`, `BMW`).

### Vehicle Interface
The **Vehicle** interface (abstract class in Python) defines two methods that every vehicle class must implement:
- `start()`: Starts the vehicle.
- `stop()`: Stops the vehicle.

### Concrete Classes
Three concrete classes (`Honda`, `Toyota`, `BMW`) implement the `Vehicle` interface. Each class provides specific implementations of the `start()` and `stop()` methods.

### Factories
Each car brand has its own factory:
- `HondaFactory`: Creates instances of `Honda`.
- `ToyotaFactory`: Creates instances of `Toyota`.
- `BMWFactory`: Creates instances of `BMW`.

## Output
The output will display the start and stop actions for the vehicles:
- Honda Car is starting
- Honda Car is stopping
- Toyota Car is starting
- Toyota Car is stopping
