# Security Checklist (What can be done in CursorAI & software-level not infrastructure!)

## Configuration Security
- [x] Detect secrets in code
- [x] Identify secrets committed to version control
- [x] Flag hardcoded credentials

## Authentication & Authorization
- [x] Identify missing authentication checks
- [x] Detect improper authorization patterns
- [x] Flag violations of principle of least privilege

## Data Protection
- [x] Identify unencrypted sensitive data
- [x] Detect missing input validation
- [x] Find XSS vulnerabilities through missing output encoding
- [x] Identify SQL injection vulnerabilities

## API Security
- [x] Detect missing rate limiting
- [x] Identify improper error handling that leaks information
- [x] Find missing input validation in API endpoints

## Logging & Monitoring
- [x] Identify sensitive information in logs
- [x] Detect missing error logging

## Dependency Management
- [x] Flag outdated dependencies with known vulnerabilities
- [x] Identify excessive dependencies that increase attack surface

## Resilience & Availability
- [x] Detect missing error handling
- [x] Identify potential DoS vulnerabilities
- [x] Find missing timeout configurations

## SDLC Security
- [x] Identify common security issues through static analysis
- [x] Suggest security improvements in code reviews
