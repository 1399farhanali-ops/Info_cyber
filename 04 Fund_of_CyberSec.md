# Fundamental of Computer security
## Identification, Authentication, and Authrization
| Concept            | Descrption           | Example                               |
|--------------------|----------------------|---------------------------------------|
|**Identification**  | Claiming on identity | Typing username                       | 
|**Authentication**  | Proving identity     | Entering password/fingerprint         |
|**Authorization**   | Granting access      | accesssing certain files after login  |
## Key principle:
"Authentication verifies who you are. Authorization decides what you can do."
##Authentication methods
- Knowledge-based: Passwords, PINs
- possession-based: smart cards, OTP tokens
- Inherence-based: Biometrics (Fingerprint, face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single Sign-on (SSO): One-time login across multiple systems (e.g., Google or Microsoft SSO)
# Authorization
- DAC (Discretionary Access Control): Owner decides who can access (Windows permission).
- MAC (Mandatory Access Control): Access based on classification levels (Militiary systems).
- RBAC (Role-Based Access Control): Permission assigned to roles (Admin, Manager, User).
- ABAC (Attribute-Based Access Control): Access Based on condition (Time, Location, User type).
## Example:
An " HR manager" role can view employee data, while "Enployee" role can only view their own profile.
#Best Practises
- Use strong, unique passwords
- Apply MFA wherever possible
- Review role-based permissions regularly
- Log all authentication access event
