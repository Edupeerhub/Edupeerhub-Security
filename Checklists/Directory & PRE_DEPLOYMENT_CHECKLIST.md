# Pre-Deployment Security Checklist

This checklist must be completed and signed off by the cybersecurity team before any new code is deployed to production.

- [ ] All code dependencies have been scanned for known vulnerabilities.
- [ ] Static Application Security Testing (SAST) has been performed.
- [ ] All sensitive credentials and secrets have been moved to environment variables or a secure vault.
- [ ] Input validation is implemented on all new user-facing endpoints.
- [ ] A penetration test has been conducted on the new features, if applicable.
- [ ] Logging and monitoring are configured to detect security events related to the new changes.
