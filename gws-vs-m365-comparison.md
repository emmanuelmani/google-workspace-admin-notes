# Google Workspace vs Microsoft 365 — Admin Comparison

A practical comparison for IT admins who know one platform and are learning the other. I built this coming from a Microsoft 365 background, so everything is mapped from the M365 perspective.

---

## Admin interfaces

| What you want to do | Microsoft 365 | Google Workspace |
|---------------------|---------------|-----------------|
| Main admin portal | admin.microsoft.com | admin.google.com |
| User management | Azure Active Directory / Entra ID | Admin Console > Directory > Users |
| Email administration | Exchange Admin Center | Admin Console > Apps > Gmail |
| Device management | Microsoft Intune | Admin Console > Devices |
| Security settings | Microsoft Defender / Purview | Admin Console > Security |
| Audit logs | Microsoft Purview Compliance | Admin Console > Reporting |
| App management | Microsoft 365 Apps admin | Admin Console > Apps > Google Workspace |

---

## User management

| Task | Microsoft 365 | Google Workspace |
|------|---------------|-----------------|
| Create user | Azure AD > New User | Admin Console > Users > Add User |
| Reset password | Azure AD > User > Reset Password | Admin Console > Users > Reset Password |
| Disable account | Azure AD > Block sign-in | Admin Console > Users > Suspend User |
| Delete account | Azure AD > Delete User | Admin Console > Users > Delete User |
| Restore deleted user | Azure AD > Deleted Users (30 days) | Admin Console > Users > Recently Deleted (20 days) |
| Bulk user creation | CSV import via Admin Center | CSV import via Admin Console |
| User groups | Microsoft 365 Groups / Security Groups | Google Groups |

---

## Authentication and MFA

| Feature | Microsoft 365 | Google Workspace |
|---------|---------------|-----------------|
| MFA product name | Microsoft Authenticator / Conditional Access | 2-Step Verification (2SV) |
| Enforce MFA for all users | Conditional Access policy | Admin Console > Security > 2-Step Verification > Enforcement |
| Supported MFA methods | Authenticator app, SMS, hardware token, FIDO2 | Authenticator app, SMS, backup codes, FIDO2, Google prompts |
| Single Sign-On | Azure AD SSO / SAML | Google Identity / SAML |
| Passwordless | Windows Hello, FIDO2 keys | Passkeys, FIDO2 keys |

---

## Device management

| Feature | Microsoft 365 | Google Workspace |
|---------|---------------|-----------------|
| MDM platform | Microsoft Intune | JAMF (third-party, preferred for Mac/iOS) or Google MDM |
| Device enrolment | Autopilot (Windows), DEP (Mac/iOS) | Apple Business Manager + JAMF, or Google MDM |
| Remote wipe | Intune > Devices > Wipe | Admin Console > Devices > Wipe |
| Compliance policies | Intune Compliance Policies | Admin Console > Devices > Mobile and Endpoints > Settings |
| App deployment | Intune > Apps | JAMF Self Service / Google Play managed |

---

## Email

| Feature | Microsoft 365 | Google Workspace |
|---------|---------------|-----------------|
| Email platform | Exchange Online | Gmail |
| Shared mailboxes | Exchange shared mailboxes | Google Groups (as collaborative inboxes) |
| Distribution lists | Distribution Groups | Google Groups |
| Email archiving | In-Place Archive / Microsoft Purview | Google Vault |
| Spam filtering | Microsoft Defender for Office 365 | Gmail spam filtering / Google Workspace security sandbox |

---

## File storage

| Feature | Microsoft 365 | Google Workspace |
|---------|---------------|-----------------|
| Personal storage | OneDrive | Google Drive (My Drive) |
| Team storage | SharePoint | Google Shared Drives |
| Default storage per user | 1TB (most plans) | 30GB pooled (Business Starter) to unlimited (higher plans) |
| Desktop sync client | OneDrive app | Google Drive for Desktop |
| Version history | SharePoint / OneDrive versioning | Google Drive version history |

---

## Security and compliance

| Feature | Microsoft 365 | Google Workspace |
|---------|---------------|-----------------|
| DLP (Data Loss Prevention) | Microsoft Purview DLP | Admin Console > Rules > DLP |
| Email archiving for compliance | Microsoft Purview / In-Place Hold | Google Vault |
| Audit logs | Unified Audit Log (Microsoft Purview) | Admin Console > Reporting > Audit |
| Retention policies | Microsoft Purview Retention | Google Vault retention rules |
| Conditional Access | Azure AD Conditional Access | Context-Aware Access (Google BeyondCorp) |
