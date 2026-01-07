# Contributing to BillSplitterMDS

We welcome contributions to the BillSplitterMDS project! This document outlines our collaboration strategy and how to contribute.

## Collaboration Strategy

We follow **GitHub Flow** for our development workflow:

1. Create a branch from `main` for your work
2. Make commits to your branch
3. Open a Pull Request when ready for review
4. Discuss and review the code
5. Merge to `main` after approval

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Git

### Setting Up the Development Environment

1. Fork and clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/BillSplitterMDS.git
   cd BillSplitterMDS
   ```

2. Install the package in development mode:
   ```bash
   pip install -e ".[dev]"
   ```

3. Run tests to verify setup:
   ```bash
   pytest
   ```

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue with:
- A clear title and description
- Steps to reproduce the bug
- Expected vs actual behavior
- Your environment (Python version, OS)

### Suggesting Features

Feature suggestions are welcome! Please open an issue with:
- A clear description of the feature
- Why it would be useful
- Any implementation ideas you have

### Making Changes

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and write tests

3. Run the test suite:
   ```bash
   pytest
   ```

4. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add feature: description of changes"
   ```

5. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

6. Open a Pull Request

### Pull Request Guidelines

- Provide a clear description of the changes
- Link any related issues
- Ensure all tests pass
- Request review from at least one team member
- Address review feedback promptly

## Code Style

- Follow PEP 8 style guidelines
- Write docstrings for all public functions (NumPy style)
- Keep functions focused and modular

## Attribution

This contributing guide is adapted from general open-source best practices and GitHub Flow guidelines.
