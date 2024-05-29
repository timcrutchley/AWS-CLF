# 04 - IAM MFA OVERVIEW

## SECTION 02 - IDENTITY ACCESS MANAGEMENT <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/28/2023 <br>

### 05/28/2024 - Reviewed

<br>

### IAM PASSWORD POLICY >>

Strong passwords = higher security for your account

In AWS you can setup a password policy:

- Set a minimum password length
- Require specific character types:
  - including uppercase letters
  - lowercase letters
  - numbers
  - non-alphanumeric characters
- Allow all IAM users to change their passwords
- Require users to change their password after some time (password expiration)
- Prevent password re-use
  <br>

### MULTI FACTOR AUTHENTICATION - MFA >>

- Users have access to your account and can possibly change configurations or delete resources in your AWS account
- You want to protect your Root Accounts and IAM users
- MFA = password _you know_ + security device _you own_

<br>

- Main benefit of MFA:
  **if a password is stolen or hacked, the account is not compromised**
  <br>

### !- MFA DEVICE OPTIONS IN AWS -! >>

**!- EXAM QUESITON -!**

<br>

**Virtual MFA Device:**

- [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_CA&gl=US) (phone only)
- [Authy](https://authy.com/) (multi-device)

<br>

**Universal 2nd Factor (U2F) Security Key**

- YubiKey by Yubico (3rd party)

<br>

**Hardware Key Fob MFA Device**

- Provided by Gemalto (3rd party),

<br>

**Hardware Key Fob MFA Device for AWS GovCloud (US)**

- Provided by SurePassID (3rd party)

<br>
