# Modeling Environment

**Modeling Environment** is an application designed to help users create and simulate various models with specific data, enabling predictions of potential future changes.

---

## Installation

Follow these steps to install and run the **Modeling Environment** project:

1. Clone the repository to your local machine:
```
git clone https://github.com/teklaos/modeling-environment.git
```

2. Navigate into the project directory:
```
cd modeling-environment
```

3. Run the program:
```
java -cp out/production/ModelingEnvironment;lib/* Main
```

---

## Key Features

- Uses Java reflection to easily add new models without modifying the core engine logic.
- Implements a custom annotation system to bind model fields to controller logic.
- Supports Groovy scripts for defining custom behavior and logic, allowing runtime extensibility and experimentation without recompilation.
