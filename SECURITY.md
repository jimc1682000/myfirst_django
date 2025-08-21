# Security Policy

## GPG Key Rotation

**Date**: 2025-08-21  
**Action**: GPG Key Update

### Previous Key (Deprecated)
- Key ID: `4AEE18F83AFDEB23`
- Status: **Revoked**
- Used for commits: 2020-10-27 to 2020-10-28
- Commits affected: 3 commits (merge pull request, README updates)

### Current Key (Active)
- Key ID: `6DCE833EFCCC91A0`
- Fingerprint: `B2BEA916373FBA236DCE833EFCCC91A0`
- Status: **Active**
- Effective from: 2025-08-21

### Reason for Change
Routine security maintenance and GPG key rotation following security best practices.

### Verification
All commits from 2025-08-21 onwards will be signed with the new key. You can verify the signature using:
```bash
git verify-commit <commit-hash>
```

### Historical Note
Previous commits signed with key `4AEE18F83AFDEB23` remain valid for the time period they were created, but the key has been revoked for security purposes.

## Reporting Security Vulnerabilities

If you discover a security vulnerability, please report it to: jimc1682000@gmail.com

---
*This security policy was established on 2025-08-21*