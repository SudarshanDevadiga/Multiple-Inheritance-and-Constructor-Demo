# Multiple Inheritance and Constructor Demo

A C++ program demonstrating multiple inheritance and constructor invocation order using a simple vehicle class hierarchy.

## Description

This program illustrates the concept of multiple inheritance in C++ by implementing a class hierarchy with `Vehicle`, `FourWheeler`, `Car`, and `Bus` classes. It demonstrates how constructors are called in a specific order when objects of derived classes are created.

### Key Features
- Multiple inheritance demonstration
- Constructor invocation order
- Class hierarchy with base and derived classes
- Simple output to show inheritance structure

## Class Structure

```cpp
class Vehicle {
public:
    Vehicle();
};

class FourWheeler {
public:
    FourWheeler();
};

class Car : public Vehicle {
public:
    Car();
};

class Bus : public Vehicle, public FourWheeler {
public:
    Bus();
};
