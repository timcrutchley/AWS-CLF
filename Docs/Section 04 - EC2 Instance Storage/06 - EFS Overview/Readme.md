# 06 - EFS OVERVIEW
## SECTION 04 - EC2 INSTANCE STORAGE<br>
### < AWS: CLOUD PRACTITIONER > <br>
### 10/09/2023 <br>
### 06/24/2024 : Reviewed <br>

<br>

### EFS - ELASTIC FILE SYSTEM >>

Managed NFS (network file system) **that can be mounted** on 100s of EC2 simultaneously

<br>

### !-EBS VS EFS-! >>
!- EXAM QUESTION -!
EBS volumes can be duplicated. However, the duplicate is just a copy, and one volume is not updated when another is.

EFS on the otherhand is a network file system. Anything on the EFS drive is shared with all that is connected to it
<br>

### !-EFS INFREQUENT ACCESS (EFS-IA)-! >>

**!-EXAM QUESTION-!**

Storage class that is cost-optimized for files not accessed every day

Up to 92% lower cost compared to EFS Standard

EFS will automatically move your files to EFS-IA based on the last time they were accessed

Enable EFS-IA with a Lifecycle Policy

Example: move files that are not accessed for 60 days to EFS-IA

Transparent to the applications accessing EFS

Cost Saving Optimization
<br>
