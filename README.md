# Seneca Polytechnic Deliveries 🚚

A comprehensive C/C++ delivery logistics system that optimizes package routing and truck assignments for efficient delivery operations.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Technologies & Tools](#technologies--tools)
- [Skills Demonstrated](#skills-demonstrated)
- [System Architecture](#system-architecture)
- [Key Features](#key-features)
- [Testing Strategy](#testing-strategy)
- [Build & Execution](#build--execution)
- [Code Structure](#code-structure)
- [Algorithms & Data Structures](#algorithms--data-structures)

## 🎯 Project Overview

This project implements a sophisticated delivery management system that assigns packages to trucks based on optimal routing algorithms, capacity constraints, and distance calculations. The system simulates real-world logistics operations with multiple delivery routes (Blue, Yellow, Green) and handles package validation, truck capacity management, and route optimization.

## 🛠️ Technologies & Tools

### Programming Languages
- **C** - Core application logic and algorithms
- **C++** - Unit testing framework integration

### Development Environment
- **Visual Studio** - IDE with IntelliSense support
- **Microsoft Visual C++** - Compiler
- **Git** - Version control system

### Testing Framework
- **Microsoft Visual Studio Unit Test Framework** - Comprehensive test suite
- **CppUnitTest.h** - C++ unit testing library

### Build Tools
- **Visual Studio Solution** (.sln)
- **MSBuild** - Build automation
- **Precompiled Headers** (PCH) - Build optimization

## 💡 Skills Demonstrated

### Software Engineering
- **Modular Design** - Clean separation of concerns with multiple header/source files
- **API Design** - Well-defined function interfaces with clear documentation
- **Memory Management** - Dynamic allocation and proper pointer handling
- **Error Handling** - Comprehensive input validation and edge case management

### Algorithms & Problem Solving
- **Pathfinding** - Shortest path algorithms for route optimization
- **Optimization** - Multi-criteria truck selection (distance, capacity, route efficiency)
- **Graph Algorithms** - Route traversal and adjacency checking
- **Sorting & Searching** - Distance-based truck prioritization

### Testing & Quality Assurance
- **Unit Testing** - 32 comprehensive test cases covering all major functions
- **Integration Testing** - Cross-module functionality validation
- **White-box Testing** - Internal logic verification
- **Edge Case Testing** - Boundary condition handling

### Data Structures
- **Structs** - Complex data modeling (Truck, PackageInfo, Route, Map)
- **Arrays** - Multi-dimensional map representation
- **Pointers** - Dynamic memory management for packages
- **Custom Data Types** - Domain-specific structures

## 🏗️ System Architecture

```
├── Core Components
│   ├── Mapping System (mapping.c/h)
│   ├── Business Logic (myFunctions.c/h)
│   ├── Data Models (myHeader.h)
│   └── Main Application (main.c)
│
├── Testing Suite
│   ├── Integration Tests
│   ├── White-box Tests
│   └── Unit Tests
│
└── Build Configuration
    ├── Project Files
    ├── Precompiled Headers
    └── Git Configuration
```

## ✨ Key Features

### 🚛 Truck Management
- **Multi-route Support** - Blue, Yellow, and Green delivery routes
- **Capacity Tracking** - Weight (2500kg) and volume (100m³) constraints
- **Dynamic Assignment** - Real-time package allocation based on optimal criteria

### 📦 Package Handling
- **Validation System** - Weight, size, and destination verification
- **Size Standards** - Support for 1, 3, and 5 cubic meter packages
- **Destination Mapping** - 25x25 grid coordinate system

### 🗺️ Route Optimization
- **Shortest Path Algorithm** - Euclidean distance calculations
- **Diversion Handling** - Alternative routing when direct delivery isn't possible
- **Adjacent Point Detection** - Efficient route planning

### 🔍 Smart Assignment Logic
- **Multi-criteria Selection** - Distance, capacity, and route efficiency
- **Load Balancing** - Optimal distribution across available trucks
- **Fallback Mechanisms** - Handling when no truck can accommodate shipment

## 🧪 Testing Strategy

### Test Coverage (32 Test Cases)
- **Integration Tests** (T1-T20) - Cross-component functionality
- **White-box Tests** (T1-T32) - Internal logic verification
- **Unit Tests** - Individual function validation

### Test Categories
1. **Validation Tests** - Shipment and truck validation
2. **Capacity Tests** - Weight and volume constraint checking
3. **Assignment Tests** - Truck selection algorithm verification
4. **Route Tests** - Path finding and optimization
5. **Edge Case Tests** - Boundary conditions and error scenarios

## 🚀 Build & Execution

### Prerequisites
- Visual Studio 2019/2022
- Windows SDK
- C/C++ build tools

### Compilation
```bash
# Open solution file
Deliveries.sln

# Build configuration
Release/Debug x64

# Run tests
Test Explorer → Run All Tests
```

### Execution
```bash
# Run main application
./main.exe

# Follow prompts for package entry
# Enter: weight size destination (e.g., "450 3 12H")
# Enter: "0 0 x" to stop
```

## 📁 Code Structure

```
sourceCode/project/
├── main.c                 # Application entry point
├── myFunctions.c/h        # Core business logic
├── myHeader.h             # Data structure definitions
├── mapping.c/h            # Map and route management
└── UnitTest/
    ├── UnitTest.cpp       # Comprehensive test suite
    ├── UnitTest.h         # Test headers
    └── pch.h/cpp          # Precompiled headers
```

## 🔢 Algorithms & Data Structures

### Key Algorithms
1. **Shortest Path Algorithm** - Custom implementation for grid-based navigation
2. **Distance Calculation** - Euclidean distance for optimal routing
3. **Capacity Optimization** - Multi-constraint satisfaction
4. **Route Selection** - Weighted scoring based on distance and capacity

### Data Structures
- **2D Arrays** - Map representation with building obstacles
- **Structures** - Complex data modeling for trucks, packages, and routes
- **Dynamic Arrays** - Package management with pointer arrays
- **Linked Structures** - Route point sequences

## 📈 Performance Considerations

- **Memory Efficiency** - Optimized struct layouts and pointer usage
- **Algorithm Complexity** - O(n) truck selection, O(n²) route optimization
- **Build Optimization** - Precompiled headers for faster compilation
- **Scalability** - Support for multiple trucks and unlimited packages

## 🎯 Real-World Applications

This project demonstrates practical software engineering skills applicable to:
- **Logistics & Supply Chain** - Delivery route optimization
- **Fleet Management** - Vehicle capacity and resource allocation
- **Geographic Information Systems** - Spatial data processing
- **Operations Research** - Multi-criteria optimization problems

## 📝 Documentation

- Comprehensive function documentation with parameter descriptions
- Clear code comments explaining complex algorithms
- Structured header files for easy API reference
- Test case documentation for verification procedures

---

**This project showcases proficiency in C/C++ programming, algorithm design, software testing, and system architecture - essential skills for software engineering roles in logistics, embedded systems, and performance-critical applications.**