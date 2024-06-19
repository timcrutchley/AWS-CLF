# 08 - EC2 INSTANCE ROLES

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/30/2023 <br>

### 06/18/2024 : Reviewed <br>

<br>

### !-IMPORTANT NOTE-! >>

**Never ever ever enter personal access key details into an EC2 instance through SSH/aws configure.**

If this is done, anyone else who logs into that instance using EC2 Connect could retrieve your personal keys.

**INSTEAD** assign roles to the EC2 instance for specific services (like IAMreadonlyaccess)
<br>
