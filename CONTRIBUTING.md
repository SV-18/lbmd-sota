# Contributing to LBMD-SOTA

We welcome contributions to LBMD-SOTA! This document provides guidelines for contributing to the project.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/yourusername/lbmd-sota.git`
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Install in development mode: `pip install -e .[dev]`

## Development Setup

```bash
# Install dependencies
pip install -r requirements.txt
pip install -e .[dev]

# Run tests
pytest tests/

# Format code
black lbmd_sota/
flake8 lbmd_sota/

# Type checking
mypy lbmd_sota/
```

## Contribution Guidelines

### Code Style
- Follow PEP 8 style guidelines
- Use type hints for all functions
- Write docstrings for all public functions and classes
- Keep line length under 100 characters

### Testing
- Write tests for new functionality
- Ensure all tests pass before submitting
- Aim for >80% code coverage

### Documentation
- Update README.md for user-facing changes
- Add docstrings for new functions/classes
- Update API documentation if needed

## Pull Request Process

1. Ensure your code follows the style guidelines
2. Add tests for new functionality
3. Update documentation as needed
4. Submit a pull request with a clear description
5. Respond to review feedback promptly

## Issue Reporting

When reporting issues, please include:
- Python version
- Operating system
- Steps to reproduce
- Expected vs actual behavior
- Error messages (if any)

## Feature Requests

We welcome feature requests! Please:
- Check existing issues first
- Provide a clear description of the feature
- Explain the use case and benefits
- Consider contributing the implementation

## Code of Conduct

Please be respectful and constructive in all interactions. We aim to create a welcoming environment for all contributors.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
