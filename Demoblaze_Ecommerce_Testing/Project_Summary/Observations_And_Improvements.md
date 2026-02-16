# Demoblaze Observations & Improvements

---

## OBS-001
### Title:
Username field allows emoji and special characters

### Description:
During signup process, system allows creating account with emoji or special characters in username field (e.g. 😀user).

### Analysis:
Functionally, system works correctly. However, allowing emoji characters in username may cause:
- Display inconsistencies
- Search issues
- Integration risks
- Data validation inconsistencies

### Recommendation:
Clarify business requirements for username validation.
Consider restricting username to:
- Alphanumeric characters
- Limited allowed symbols (_ . -)

### Severity:
Low

### Type:
Improvement / Requirement Clarification

