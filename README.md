
# 🚚 RouteX: Package Delivery Simulation System

A structured and test-driven C-based simulation that models a package delivery system using trucks on a 25x25 map grid. Developed through a milestone-based SDLC and Agile workflow to master system design, collaborative development, and automated testing.

---

## 📦 Project Overview

This program simulates how packages are assigned to delivery trucks based on location, distance, truck capacity (volume/weight), and delivery routes. It parses a map of Seneca College campus and efficiently distributes packages using logic mimicking real-world logistics.

---

## 🔄 Software Development Life Cycle (SDLC)

| **Phase**                | **Description**                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| **1. Requirements**      | Collected functional and non-functional requirements via milestone guidelines. |
| **2. Analysis**          | Defined system behavior, constraints, and delivery conditions.                 |
| **3. Design**            | Structured modules using `.h` and `.c` files; planned route logic, data flows. |
| **4. Implementation**    | Wrote modular, reusable C code with clear separation of concerns.              |
| **5. Testing**           | Extensive blackbox, whitebox, integration, and acceptance testing.             |
| **6. Deployment**        | Packaged and shared with test output, traceability matrix, and documentation.  |
| **7. Maintenance**       | Iteratively improved through 3 milestone submissions and SCRUM reviews.        |

📁 All artifacts for each phase are documented in `/Documentation/`, `/Testing/`, and `/Source/`.

---

## ⚙️ Agile Development & Testing

Gained experience in an industry-like development and test automation environment, adhering to SDLC and Agile methodologies. Designed software, developed automated test suites with 100 test cases, and used GitHub for collaboration and Jira to track and resolve 18+ bugs. Achieved 85% test coverage and delivered a high-quality product with 90% of test cases passed.

---

## 🧠 Key Features

- **Structured Programming in C**
- **Efficient Route & Truck Assignment Logic**
- **Predefined Grid-Based Mapping**
- **Extensive Test Coverage**
- **Agile + SDLC Documentation**
- **Collaborative Development with GitHub & Jira**

---

## 🔧 Technologies Used

- **Language**: C (GCC / MSVC)
- **Tools**: Visual Studio, Custom Unit Testing Suite
- **Version Control**: Git & GitHub
- **Project Management**: Jira, SCRUM
- **Testing Approaches**: Blackbox, Whitebox, Integration, Acceptance
- **Documentation**: Markdown (`.md`), Reports, Traceability Matrix

---

## 📁 Project Structure

```
📦 Project Root
├── 📂 .vs/                       # Visual Studio solution files
├── 📂 Output/                    # Test result outputs, screenshots
├── 📂 Source/
│   ├── main.c                   # Entry point
│   ├── mapping.c/h              # Map parsing and grid logic
│   ├── myFunctions.c/h          # Business logic and helpers
│   └── test_main.c              # Unit test driver
├── 📂 Testing/
│   ├── Blackbox Testing/
│   ├── Whitebox Testing/
│   ├── Acceptance Testing/
│   ├── Integration Testing/
│   └── Traceability Matrix/
├── 📂 Documentation/
│   ├── GroupContract/
│   ├── FunctionSpecification/
│   └── SDLC Artifacts/
└── README.md
```

---

## 🧪 Testing Strategy

This project demonstrates disciplined, multi-layered testing:

- ✅ **100+ Automated Test Cases**
- ✅ **Blackbox Testing**
- ✅ **Whitebox Testing**
- ✅ **Integration Testing**
- ✅ **Acceptance Testing**
- ✅ **Traceability Matrix** linking tests to requirements
- ✅ **85% Test Coverage** achieved

Test logs and screenshots are available under `/Output/`.

---

## ▶️ How to Compile and Run

### 🖥️ On Visual Studio (Windows)
1. Open `.sln` file.
2. Build Solution.
3. Run `main.c` or `test_main.c`.

### 💻 On Linux/macOS (GCC)
```bash
gcc main.c mapping.c myFunctions.c -o delivery_sim
./delivery_sim
```

### 🧪 Run Tests
```bash
gcc test_main.c mapping.c myFunctions.c -o tests
./tests
```

---

## 🧑‍💻 Skills Demonstrated

| Category              | Skillset                                                              |
|-----------------------|-----------------------------------------------------------------------|
| Programming           | Pointers, structs, modular design, file I/O                          |
| Software Engineering  | SDLC, requirement analysis, Agile, testing strategy                  |
| Teamwork              | SCRUM, GitHub collaboration, task delegation                         |
| Algorithms            | Euclidean distance, route selection, optimization                    |
| Testing               | Test suite development, bug tracking (Jira), traceability matrix     |
| Documentation         | SDLC documentation, markdown, reports, Jira logs                     |

---

## 📈 Sample Output

```
Package at (4,8) assigned to GREEN Truck 1 (93% full)
Package at (16,2) assigned to BLUE Truck 2 (82% full)
Package at (8,14) assigned to YELLOW Truck 3 (85% full)
```

---

## 📌 Status

✅ Final milestone submitted  
📦 100+ test cases with 85% coverage  
🧪 Agile development with Jira, SDLC documents  
📁 Ready for demonstration and grading  

---

## 🚀 Future Enhancements

- Implement pathfinding algorithms (Dijkstra, A*)
- Real-time package queue handling
- UI/CLI improvements for map visualization

---