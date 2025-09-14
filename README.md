# Specs Language Support

This extension adds syntax highlighting and icon support for `.specs` files.  
It is designed for defining microservices, routes, and formal verification sequences.

## Features
- Syntax highlighting for `.specs` keywords, operators, and identifiers.
- Custom file icon for `.specs` files.
- Support for sequences, constraints, and service definitions.

## Usage
1. Install the extension.
2. Open a `.specs` file.
3. Enjoy syntax highlighting and proper icons!

## Example

```specs
services:
    OrderService
    PaymentService

routes:
    endpoint1 = "/order";
    endpoint2 = "/payment";

seq:
    endpoint1 -> endpoint2
