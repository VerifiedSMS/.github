# Contributing to VerifiedSMS SDKs

First off, thank you for considering contributing to VerifiedSMS! It's people like you that make our SDKs better for everyone.

## Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs

- **Check if the bug already exists** – search the issue tracker for the specific SDK repository.
- **Use a clear title and description** – include steps to reproduce, expected behavior, and actual behavior.
- **Add relevant details** – OS, language version, SDK version, code snippet (if possible).

### Suggesting Enhancements

- Open an issue with the label `enhancement`.
- Explain why this enhancement would be useful to most users, not just you.
- If possible, provide a rough implementation idea.

### Pull Requests

1. **Fork the repository** you want to contribute to.
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`).
3. **Make your changes** – add tests if applicable.
4. **Run the tests** – ensure everything passes.
5. **Commit your changes** with a clear message (`git commit -m 'Add some amazing feature'`).
6. **Push to your fork** (`git push origin feature/amazing-feature`).
7. **Open a Pull Request** against the `main` branch of the original repository.

## Development Setup

Each SDK repository contains its own setup instructions. Generally:

```bash
# Clone your fork
git clone https://github.com/your-username/sdk-python.git
cd sdk-python

# Install dependencies (example for Python)
pip install -r requirements-dev.txt

# Run tests
pytest