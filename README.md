# code-smells-calculator

> Code Smells & Metrics Calculator in C++

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/code-smells-calculator)
![License](https://img.shields.io/github/license/J1u2a3n8/code-smells-calculator)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/code-smells-calculator)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/code-smells-calculator?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/code-smells-calculator)

## Description

A C++ tool that analyzes source code to detect code smells (Long Method, Large Class, Feature Envy, etc.) and calculate software metrics (Cyclomatic Complexity, Coupling, Cohesion, Maintainability Index). Built with Clang/LLVM.

## Architecture

Clang AST-based: Frontend → AST Traversal → Metrics Computation → Smell Detection → Report Generator

## Quick Start

### Prerequisites

.NET 8 SDK, Visual Studio 2022 / VS Code with C# Dev Kit

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/code-smells-calculator.git
cd code-smells-calculator

mkdir build && cd build && cmake .. && make
```

### Usage

```bash
./CodeSmellsCalculator --input ./source --output report.json --format json
```

## Testing

```bash
ctest --output-on-failure
```

## Project Structure

```
code-smells-calculator/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

C++, CMake, Clang/LLVM (libTooling, libAST), JSON for Modern C++

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://www.linkedin.com/in/juan-luis-canedo-villarroel-189783227/)

---

⭐ If you found this project useful, give it a star!
