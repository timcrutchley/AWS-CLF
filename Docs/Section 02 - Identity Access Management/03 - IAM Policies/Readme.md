# 03 - IAM POLICIES

## SECTION 02 - IDENTITY ACCESS MANAGEMENT <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/27/2023 <br>

<br>

### IAM POLICIES STRUCTURE >>

**Consists of:**

- **Version:** policy language version, always include "2012-10-17"
- **Id:** an identifier for the policy (optional)
- **Statement:** one or more individual statements (required)

**Statements consist of**

- **Sid:** an identifier for the statement (optional)
- **Effect:** whether the statement allows or denies access (Allow, Deny)
- **Principal:** account/user/role to which this policy applied to
- **Action:** list of actions this policy allows or denies
- **Resource:** list of resources to which the actions applied to
- **Condition:** conditions for when this policy is in effect (optional)
  <br>
