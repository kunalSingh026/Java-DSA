# Data Structures & Algorithms (Java DSA)
Welcome to the **Java DSA** repository! This project contains clean, well-structured Java implementations of essential Data Structures, Algorithms, and coding exercises. It serves as a personal learning resource, reference guide, and practice hub.
## 📂 Project Structure
Here is the directory structure of the repository, categorised by topics:
```text
├── Backtracking/
│   └── N_Queens.java             # Solves the classic N-Queens puzzle
├── Recursion/
│   └── TowerOfHanoi.java         # Solves the Tower of Hanoi puzzle using recursion
├── Sorting/
│   ├── Bubble_Sort.java          # In-place, stable comparison bubble sort
│   ├── InsertionSort.java        # Simple insertion-based sorting algorithm
│   ├── Merge_Sort.java           # Divide-and-conquer merge sort algorithm
│   └── Quick_Sort.java           # Divide-and-conquer quick sort using pivoting
├── Bits.java                     # Bit manipulation utilities and examples
├── Rectangle.java                # Nested loop practice printing a star rectangle pattern
└── DryRun.excalidraw             # Drawing/diagram file for dry-running algorithms
```
---
## 🛠️ Getting Started
### Prerequisites
To run the code in this repository, make sure you have the Java Development Kit (JDK) installed:
- **Recommended version:** JDK 17 or higher.
### Compiling and Running
You can compile and run any of the files using your terminal.
1. Navigate to the root directory of the project:
   ```bash
   cd "Java DSA"
   ```
2. **Compile a file:**
   - For root-level files (e.g., `Rectangle.java`):
     ```bash
     javac Rectangle.java
     ```
   - For package-nested files (e.g., `Sorting/Quick_Sort.java`):
     ```bash
     javac Sorting/Quick_Sort.java
     ```
3. **Run a file:**
   - Root-level files:
     ```bash
     java Rectangle
     ```
   - Package-nested files:
     ```bash
     java Sorting.Quick_Sort
     ```
---
## ⚙️ Automated Integration (CI)
This repository includes a GitHub Actions CI workflow located at [java-ci.yml](.github/workflows/java-ci.yml) which automatically checks code correctness on every push or pull request to the `main` branch.
- **Workflow Action:** Sets up JDK 17 (Temurin distribution) and compiles all `.java` files recursively to verify compilation success.
---
## 🎨 Visualisation and Dry Runs
- The repository includes a `DryRun.excalidraw` file at the root. You can open this file using [Excalidraw](https://excalidraw.com/) to view or create visual traces and diagrams of recursion trees, backtracking paths, or memory layout dry runs.
