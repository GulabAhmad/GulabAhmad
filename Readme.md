# Gulab Don

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![UV](https://img.shields.io/badge/package%20manager-UV-green.svg)](https://github.com/astral-sh/uv)

A modern Python project built with UV package manager for efficient dependency management and fast development workflows.

## 🚀 Features

- **Fast Package Management**: Built with UV for lightning-fast dependency resolution
- **Modern Python**: Compatible with Python 3.8+
- **Clean Architecture**: Well-structured and maintainable codebase
- **Easy Setup**: Simple installation and configuration process

## 📋 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## 🛠️ Installation

### Prerequisites

- Python 3.8 or higher
- UV package manager

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gulab-don.git
   cd gulab-don
   ```

2. **Install dependencies using UV**
   ```bash
   uv sync
   ```

3. **Activate the virtual environment**
   ```bash
   uv shell
   ```

## 🎯 Usage

### Running the Application

```bash
# Run the main application
uv run python main.py

# Run tests
uv run pytest

# Run linting
uv run ruff check .
```

### Development

```bash
# Install development dependencies
uv add --dev pytest ruff black

# Format code
uv run black .

# Check code quality
uv run ruff check .
```

## 🏗️ Project Structure

```
gulab-don/
├── src/                    # Source code
│   ├── __init__.py
│   └── main.py
├── tests/                  # Test files
│   └── __init__.py
├── docs/                   # Documentation
├── pyproject.toml         # Project configuration
├── README.md              # This file
└── .gitignore            # Git ignore rules
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Run tests**
   ```bash
   uv run pytest
   ```
5. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Development Guidelines

- Follow PEP 8 style guidelines
- Write comprehensive tests for new features
- Update documentation as needed
- Use meaningful commit messages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [UV](https://github.com/astral-sh/uv) for fast Python package management
- Thanks to all contributors who have helped with this project

## 📞 Contact

- **Author**: [Your Name]
- **Email**: [your.email@example.com]
- **GitHub**: [@yourusername](https://github.com/yourusername)

---

⭐ If you found this project helpful, please give it a star!