# Contributing to GMTSAR-AIT

We welcome contributions to GMTSAR-AIT! This document provides guidelines for contributing to the project.

## Ways to Contribute

- **Bug Reports**: Submit detailed bug reports with reproducible examples
- **Feature Requests**: Suggest new features or improvements
- **Code Contributions**: Submit pull requests with bug fixes or new features
- **Documentation**: Improve documentation, tutorials, or examples
- **Testing**: Help test the software on different Ubuntu versions or configurations

## Getting Started

1. **Fork the Repository**: Create a fork of the GMTSAR-AIT repository on GitHub
2. **Clone Your Fork**: Clone your fork to your local machine
3. **Set Up Development Environment**: Ensure you have a Ubuntu LTS system for testing
4. **Create a Branch**: Create a feature branch for your changes

```bash
git clone https://github.com/yourusername/GMTSAR-auto-installation-tool.git
cd GMTSAR-auto-installation-tool
git checkout -b feature/your-feature-name
```

## Development Guidelines

### Code Style

- **Shell Scripts**: Follow bash best practices and include comprehensive error handling
- **Comments**: Add clear comments explaining complex logic
- **Error Messages**: Provide informative error messages for troubleshooting
- **Logging**: Include appropriate logging for installation steps

### Testing

- **Test on Multiple Ubuntu Versions**: Ensure compatibility across Ubuntu LTS releases
- **Clean Environment Testing**: Test installations on fresh Ubuntu systems
- **Regression Testing**: Verify that changes don't break existing functionality
- **Edge Cases**: Test error conditions and unusual system configurations

### Documentation

- **Code Documentation**: Document functions and complex procedures
- **User Documentation**: Update README.md for user-facing changes
- **Changelog**: Document significant changes in commit messages

## Submitting Changes

### Pull Request Process

1. **Update Documentation**: Ensure documentation reflects your changes
2. **Test Thoroughly**: Test your changes on clean Ubuntu systems
3. **Write Clear Commit Messages**: Use descriptive commit messages
4. **Create Pull Request**: Submit a pull request with a clear description

### Pull Request Template

```markdown
## Description
Brief description of changes made.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Refactoring

## Testing
- [ ] Tested on Ubuntu 20.04
- [ ] Tested on Ubuntu 22.04
- [ ] Tested clean installation
- [ ] Tested upgrade scenario

## Checklist
- [ ] Code follows project style guidelines
- [ ] Self-review of code completed
- [ ] Documentation updated
- [ ] No new warnings introduced
```

## Reporting Issues

### Bug Reports

When reporting bugs, please include:

- **Ubuntu Version**: Specific version and architecture
- **Error Messages**: Complete error messages and stack traces
- **Reproduction Steps**: Step-by-step instructions to reproduce the issue
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Environment**: Any relevant system information

### Feature Requests

When requesting features, please include:

- **Use Case**: Describe the problem or need
- **Proposed Solution**: Suggest how the feature might work
- **Alternatives**: Consider alternative solutions
- **Additional Context**: Any other relevant information

## Code of Conduct

This project adheres to a code of conduct. By participating, you are expected to uphold this code.

### Our Standards

- **Be Respectful**: Treat all contributors with respect and kindness
- **Be Inclusive**: Welcome contributors from all backgrounds
- **Be Constructive**: Provide constructive feedback and criticism
- **Be Patient**: Remember that everyone has different experience levels

### Unacceptable Behavior

- Harassment or discrimination of any kind
- Trolling, insulting, or derogatory comments
- Public or private harassment
- Publishing others' private information without permission

## Getting Help

If you need help with contributing:

- **Documentation**: Check the README.md and existing documentation
- **Issues**: Search existing issues for similar problems
- **Discussions**: Use GitHub Discussions for questions
- **Contact**: Reach out to maintainers via email

## Recognition

All contributors will be acknowledged in the project. Significant contributors may be invited to become maintainers.

## License

By contributing to GMTSAR-AIT, you agree that your contributions will be licensed under the MIT License.

## Development Setup

For detailed development setup instructions:

1. **Prerequisites**: Ubuntu LTS system, git, bash
2. **Dependencies**: Install development tools if needed
3. **Testing Environment**: Set up isolated testing environments
4. **Virtual Machines**: Consider using VMs for clean testing

Thank you for contributing to GMTSAR-AIT!
