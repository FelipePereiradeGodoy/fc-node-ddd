
# fc-node-ddd

Project for studying Domain-Driven Design (DDD) in Node.js.

## Purpose
This repository aims to demonstrate, in a practical way, the main DDD concepts applied to a Node.js architecture using TypeScript.

## Main concepts covered
- Entities, Value Objects, and Aggregates
- Repositories and Domain Services
- Domain Events and Handlers
- Factories
- Separation between domain and infrastructure layers

## Project structure
The project is organized into folders that reflect business contexts (Customer, Product, Checkout) and DDD concepts:

- `src/domain`: Domain layer, with entities, events, repositories, services, and value objects.
- `src/infrastructure`: Persistence and integration implementations (e.g., Sequelize).

## How to run
1. Install dependencies:
	```bash
	npm install
	```
2. Run the tests:
	```bash
	npm test
	```

## Notes
This project is intended for educational purposes and experimentation with DDD concepts.
