# Security Policy

## Supported Versions

I am committed to maintaining the security of OmniPost. The following versions are currently supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

I take security vulnerabilities seriously. If you discover a security issue, please follow these steps:

### How to Report

1. **Do NOT** open a public GitHub issue for security vulnerabilities
2. **Contact me directly** through one of these methods:
   - Open a private vulnerability report on GitHub (recommended)
   - Email me through my GitHub profile
   - Contact me via [john-ogletree.github.io](https://john-ogletree.github.io)

### What to Include

Please provide as much information as possible in your report:

- **Description** of the vulnerability
- **Steps to reproduce** the issue
- **Impact** of the vulnerability
- **Potential fixes** (if you have suggestions)
- **Your contact information** (optional, for follow-up)

### Response Time

I aim to respond to security reports within:

- **Initial response**: Within 48 hours
- **Status update**: Within 5 business days
- **Fix timeline**: Depending on complexity, typically within 2 weeks

## Security Measures

### Data Protection

- OmniPost runs entirely in your browser
- No data is sent to any server
- All processing happens locally on your device
- No cookies or tracking are used
- No personal information is collected or stored

### Code Security

- Uses vanilla JavaScript to minimize dependencies
- No external libraries beyond Tailwind CSS (loaded via CDN)
- All canvas rendering is done client-side
- No file uploads are processed server-side
- No database or external storage is used

### Content Security Policy (CSP)

The application follows these security practices:

- Only loads resources from trusted CDNs
- Uses secure HTTPS connections
- No inline scripts (except for functionality)
- No eval() or similar dangerous functions

## Known Security Issues

Currently, there are no known security vulnerabilities in OmniPost. If you discover any, please report them using the process above.

## Best Practices for Users

To ensure your security when using OmniPost:

1. **Keep your browser updated** - Always use the latest version of your browser
2. **Use HTTPS** - Access the application via HTTPS when hosted online
3. **Verify downloads** - Only download OmniPost from the official repository
4. **Review permissions** - The application should not request any unnecessary permissions
5. **Be cautious with exports** - Exported images may contain personal information you choose to include

## Security Patches

Security patches will be released as new versions:

- **Critical vulnerabilities**: Patched immediately with a new version release
- **High severity**: Patched within 7 days
- **Medium severity**: Patched within 30 days
- **Low severity**: Patched in the next scheduled release

## Vulnerability Disclosure Process

1. **Report received** - I acknowledge receipt within 48 hours
2. **Investigation** - I verify and assess the vulnerability
3. **Fix development** - I develop and test a fix
4. **Release** - I release a new version with the fix
5. **Disclosure** - I publicly disclose the vulnerability after the fix is released

## Bug Bounty

Currently, I do not offer a bug bounty program. However, I greatly appreciate security researchers who responsibly disclose vulnerabilities. Contributors who help improve security will be recognized in the project's README.

## Security Contact

For all security-related matters, please contact me through:

- **GitHub**: [john-ogletree](https://github.com/john-ogletree)
- **Website**: [john-ogletree.github.io](https://john-ogletree.github.io)

## Third-Party Dependencies

OmniPost uses the following third-party resources:

| Resource | Purpose | Security Notes |
|----------|---------|----------------|
| Tailwind CSS | Styling | Loaded from CDN, used for UI only |

All dependencies are loaded over HTTPS and are from trusted sources.

## Responsible Disclosure

I believe in responsible disclosure. If you discover a vulnerability:

1. Report it privately first
2. Allow reasonable time for me to fix it
3. Do not publicly disclose it until I've released a fix
4. Do not exploit the vulnerability for any purpose

## Compliance

OmniPost is designed to be:

- **GDPR compliant**: No data collection, no cookies
- **CCPA compliant**: No personal information processed
- **COPPA compliant**: No data collection from children
- **Accessibility focused**: Continually improving accessibility

## Secure Development Practices

I follow these practices to maintain security:

- Regular dependency updates
- Code reviews for all changes
- Testing across multiple browsers
- Staying informed about security best practices
- Minimizing external dependencies

## Version History

| Version | Security Updates |
|---------|------------------|
| 1.0.0   | Initial release with standard security practices |

## Future Security Roadmap

I plan to enhance security by:

- Implementing a Content Security Policy header
- Adding Subresource Integrity (SRI) for CDN resources
- Improving accessibility and security testing
- Adding more robust error handling

## Acknowledgments

I appreciate the security researchers and community members who help keep OmniPost secure. Your contributions make the web a safer place.

---

**Last Updated**: August 2026

---

**Questions?** If you have any questions about this security policy, please contact me through my [GitHub profile](https://github.com/john-ogletree) or visit [john-ogletree.github.io](https://john-ogletree.github.io).
