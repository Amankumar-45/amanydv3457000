# Contributing to Intelli-Credit

Thank you for your interest in contributing to Intelli-Credit! We welcome contributions from the community.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/amanydv3457000.git`
3. Create a new branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Submit a pull request

## Development Setup

### Prerequisites
- Python 3.8+
- pip and virtualenv
- PostgreSQL or MongoDB

### Setup Instructions

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env

# Run tests
pytest

# Start development server
python app.py
```

## Code Standards

### Python Code Style
- Follow PEP 8 guidelines
- Use 4 spaces for indentation
- Use meaningful variable names
- Add docstrings to functions and classes
- Write type hints where possible

### Example:
```python
def calculate_credit_score(
    income: float,
    debt: float,
    history: int
) -> float:
    """
    Calculate credit score based on financial metrics.
    
    Args:
        income: Annual income in dollars
        debt: Total debt amount in dollars
        history: Years of credit history
        
    Returns:
        float: Credit score between 0 and 1000
    """
    pass
```

### Testing
- Write tests for new features
- Maintain test coverage above 80%
- Use pytest for testing
- Follow test naming convention: `test_*.py`

### Git Commit Messages
- Use clear, descriptive messages
- Present tense: "Add feature" not "Added feature"
- Reference issues: "Fix #123"
- Keep first line under 50 characters

### Documentation
- Update README.md for significant changes
- Add docstrings to new functions
- Include examples in documentation
- Document new API endpoints

## Pull Request Process

1. Update README.md with any new functionality
2. Update requirements.txt with new dependencies
3. Ensure all tests pass: `pytest`
4. Ensure code follows style guidelines
5. Request review from maintainers
6. Address feedback and comments

## Reporting Issues

When reporting issues, please include:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Python version and dependencies
- Error messages or logs

## Feature Requests

We welcome feature requests! Please:
- Describe the feature clearly
- Explain the use case
- Provide examples if possible
- Consider backward compatibility

## Questions?

Feel free to open an issue or contact the maintainers.

Thank you for contributing! 🎉