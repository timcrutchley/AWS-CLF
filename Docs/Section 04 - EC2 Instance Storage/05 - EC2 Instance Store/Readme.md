# 05 - EC2 INSTANCE STORE
## SECTION 04 - EC2 INSTANCE STORAGE<br>
### < AWS: CLOUD PRACTITIONER > <br>
### 10/09/2023 <br>

<br>

### EC2 INSTANCE STORE >>

EBS volumes are network drives with good but "limited" performance
If you need a high-performance hardware disk, use EC2 Instance Store

Better I/O performance
EC2 Instance Store lose their storage if they're stopped (ephemeral)
Good for buffer/cache/scratch data/temporary content
Risk of data loss if hardware fails
Backups and Replication are your responsibility
<br>