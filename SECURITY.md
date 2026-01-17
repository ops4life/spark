# 🔒 Security Policy

## Supported Versions

We actively maintain and provide security updates for the following:

| Project | Supported |
|---------|-----------|
| All active ops4life repositories | ✅ |

## Reporting a Vulnerability

We take security seriously. If you discover a security vulnerability in any ops4life project, please report it responsibly.

### 📧 How to Report

1. **Do NOT** open a public issue for security vulnerabilities
2. Use [GitHub Private Vulnerability Reporting](https://github.com/ops4life/spark/security/advisories/new)
3. Or contact maintainers directly via GitHub

### 📝 What to Include

- Description of the vulnerability
- Steps to reproduce
- Affected project(s) and version(s)
- Potential impact
- Suggested fix (if any)

### ⏱️ Response Timeline

| Action | Timeframe |
|--------|-----------|
| Initial response | 48 hours |
| Status update | 7 days |
| Fix timeline | Depends on severity |

### 🏆 Recognition

We appreciate responsible disclosure. Contributors who report valid security issues will be:

- Credited in the security advisory (unless anonymity is preferred)
- Thanked publicly in release notes

## Security Best Practices

When contributing to ops4life projects:

- ❌ Never commit secrets, API keys, or credentials
- ❌ Never hardcode sensitive information
- ✅ Use environment variables for secrets
- ✅ Follow least privilege principles
- ✅ Keep dependencies updated

## Security Tools We Use

| Tool | Purpose |
|------|---------|
| Gitleaks | Secret scanning |
| CodeQL | Code vulnerability analysis |
| Dependabot | Dependency updates |
| Trivy | Container scanning |

## Questions

For general security questions, open a discussion in the [Q&A category](https://github.com/ops4life/spark/discussions/categories/q-a).
