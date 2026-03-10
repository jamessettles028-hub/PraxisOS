# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | Yes |
| Previous releases | No |

Only the latest deployed version of PraxisOS receives security attention. Since PraxisOS is a frontend-only application with no backend or cloud services, the attack surface is limited to the browser environment and local file system interactions.

## Reporting a Vulnerability

If you discover a security vulnerability in PraxisOS, please report it responsibly:

1. **Do NOT open a public GitHub issue.** Security vulnerabilities must be reported privately.
2. **Use GitHub's private security advisory:**
   - Go to the [Security Advisories page](https://github.com/Reddidgy/PraxisOS/security/advisories/new) and create a new private advisory.
3. **Alternatively, email us** at the address listed in the repository owner's GitHub profile.

### What to Include

- A clear description of the vulnerability
- Steps to reproduce
- Potential impact assessment
- Suggested fix (if any)

## Response Timeline

- **Acknowledgment:** We will acknowledge your report within 5 business days.
- **Investigation:** We will investigate and provide an initial assessment within 10 business days.
- **Resolution:** We do not guarantee a specific patch timeline, but we will keep you informed of progress and prioritize based on severity.

## Scope

Since PraxisOS runs entirely in the browser with no server component, the following are in scope:

- Cross-site scripting (XSS) via task content or file rendering
- File System Access API misuse leading to unintended file operations
- Data leakage through browser APIs or third-party dependencies
- Supply chain vulnerabilities in dependencies

The following are out of scope:

- Vulnerabilities requiring physical access to the user's machine
- Browser-level vulnerabilities (report these to the browser vendor)
- Social engineering attacks

## Recognition

We appreciate responsible disclosure. With your permission, we will credit reporters in the release notes for any confirmed vulnerability.
