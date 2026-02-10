# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Currently supported versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.x     | :white_check_mark: |

## Reporting a Vulnerability

We take the security of this project seriously. If you discover a security vulnerability, please follow these steps:

### How to Report

1. **Do not** open a public issue
2. Email security concerns to the repository maintainers
3. Include as much information as possible:
   - Type of vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### What to Expect

- **Acknowledgment**: We will acknowledge receipt of your vulnerability report within 48 hours
- **Updates**: We will send you regular updates about our progress
- **Disclosure**: We will work with you to understand and resolve the issue before any public disclosure
- **Credit**: We will credit you for the discovery (unless you prefer to remain anonymous)

## Security Updates

### Automated Dependency Updates

This repository uses Dependabot to automatically monitor and update dependencies:
- GitHub Actions are checked monthly
- NuGet packages are checked weekly
- npm packages are monitored for security vulnerabilities

### Manual Security Review

We recommend:
1. Regularly reviewing dependency updates from Dependabot
2. Enabling GitHub Security Advisories
3. Using CodeQL for code scanning
4. Following secure coding practices

## Security Best Practices

When contributing to this project, please:

1. **Dependencies**: Keep all dependencies up to date
2. **Secrets**: Never commit sensitive information (API keys, passwords, tokens)
3. **Input Validation**: Validate all user inputs
4. **Code Review**: All changes should be reviewed before merging
5. **Testing**: Include security test cases where applicable

## Known Security Features

- Dependabot enabled for automated dependency updates
- MIT License for transparency
- Regular security monitoring

## Contact

For security-related questions or concerns, please contact the repository maintainers through GitHub.

---

Thank you for helping keep this project secure!
