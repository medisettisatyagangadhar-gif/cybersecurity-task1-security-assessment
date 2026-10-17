# Identified Risks

| No. | Risk | Level | Recommendation |
|---|---|---|---|
| 1 | SQL Injection in login | High | Parameterized queries |
| 2 | Cross-Site Scripting (XSS) | High | Output encoding, CSP |
| 3 | Weak authentication / no rate limit | High | Strong passwords, MFA, lockout |
| 4 | Broken access control (IDOR) | High | Server-side ownership checks |
| 5 | Sensitive data exposure (public folder) | Medium | Restrict access |
| 6 | Security misconfiguration (errors, headers) | Medium | Hide errors, add headers |
| 7 | Weak input validation | Medium | Server-side validation |
| 8 | No HTTPS (local setup) | Low | Use HTTPS |
