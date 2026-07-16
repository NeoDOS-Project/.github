# Contributing to NeoDOS

Thank you for your interest in contributing to NeoDOS.

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold a respectful and inclusive environment.

## How to Contribute

### Reporting Issues

1. Use the appropriate issue template (bug, feature, improvement)
2. Be descriptive: include reproduction steps, logs, and environment
3. Label the issue appropriately

### Submitting Pull Requests

1. Fork the repository
2. Create a descriptive branch: `feat/name`, `fix/name`, `refactor/name`
3. Follow the project's code style
4. Ensure all tests pass
5. Update documentation if needed
6. Open a Pull Request using the template

### Code Standards

- Rust nightly, `no_std` for kernel-space
- Naming: `snake_case` for functions/variables, `PascalCase` for types/enums/traits
- Tests required for all new kernel code
- Comments in English (Spanish in user-facing strings is acceptable)

### Review Process

1. A maintainer will review your PR
2. CI must pass (build + tests + lints)
3. At least one approval required before merging

## Development Setup

See [README.md](https://github.com/NeoDOS-Project/NeoDOS#readme) for build and test instructions.

## License

By contributing, you agree that your contributions are licensed under MIT.
