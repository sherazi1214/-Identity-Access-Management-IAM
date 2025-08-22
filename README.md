# -Identity-Access-Management-IAM

**English:**
IAM is a framework of policies, processes, and technologies that ensures the right individuals have the right access to the right resources at the right time.

**Key Goals of IAM:**

**Authentication** → Verify who you are (username/password, MFA).

**Authorization** → What you can access (files, apps, systems).

**Accountability** → Track what actions you performed (logs, audits).

**Urdu:**
IAM ka kaam hai ke user ki identity confirm karna aur usko sahi access dena, aur har action ko track karna.

## IAM Lifecycle

![Identity-Access-Management-IAM](https://www.business-analysis.com.au/wp-content/uploads/2020/03/Screen-Shot-2020-09-18-at-10.36.09-am.png)

### IAM follows a user identity lifecycle, from join → move → leave.

##1. Identity Provisioning (Onboarding)

**English:**

When a new user (employee, partner, customer) joins, an identity is created in the system.

User is assigned initial credentials, roles, and permissions.

**Example:** New employee gets an AD account, email ID, and access to HR portal.

 **Urdu:**
Yani jab banda naya join karta hai, uska account ban jata hai aur initial access mil jata hai.

### 2. Access Management (Authorization & Authentication)

**English:**

User access is controlled by authentication (passwords, MFA, biometrics) and authorization (role-based or attribute-based).

Ensures users only access resources they are permitted to.

**Urdu:**
Ye stage decide karta hai ke kaunsa user kahan jaa sakta hai aur kahan block hoga.

### 3. Identity Administration (Ongoing Management / Modification)

**English:**

Handles changes during user lifecycle (role change, department transfer, promotion).

Access rights are updated accordingly (principle of least privilege).

**Example:** If HR employee moves to IT, HR system access is removed, IT tools access is granted.

**Urdu:**
Agar banda department change kare ya promotion ho, uska access modify hota hai.

### 4. Identity Monitoring (Audit & Compliance)

**English:**

Regularly monitor access logs, unusual activities, and compliance.

Detect identity misuse or insider threats.

Supports auditing (ISO, HIPAA, GDPR compliance).

**Urdu:**
Ye stage ensure karta hai ke koi misuse na ho aur har action log ho.

### 5. Identity De-Provisioning (Offboarding / Termination)

**English:**

When user leaves the organization, all access must be revoked immediately.

Prevents ex-employees from accessing systems.

**Example:** Disable AD account, remove email, revoke VPN access.

**Urdu:**
Jab banda leave ya resign karta hai, uska sara access turant band kar diya jata hai.

### IAM Lifecycle Summary (One-liners Roman Urdu)

**Provisioning** → New user account create.

**Access Management** → Control login + resources.

**Administration** → Update access as role changes.

**Monitoring** → Logs, audit, compliance.

**De-provisioning** → Access revoke on exit.
