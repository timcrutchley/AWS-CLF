# 02 - EBS SNAPSHOT

## SECTION 04 - EC2 INSTANCE STORAGE<br>

### < AWS: CLOUD PRACTITIONER > <br>

### 10/02/2023 <br>

### 06/22/2024 : Reviewed <br>
<br>

### EBS SNAPSHOTS >>

Make a backup (snapshot) of your EBS volume at a point in time

<br>

Not necessary to detach volume to do snapshot, but recommended

<br>

Can copy snapshots across AZ or Region

<br>

### EBS SNAPSHOTS FEATURES >>

**EBS Snapshot Archive**

- Move a Snapshot to an "archive tier" that is 75% cheaper
- Takes 24 to 72 hours for restoring the archive

**Recycle Bin for EBS Snapshots**

- Setup rules to retain deleted snapshots so you can recover them after an accidental deletion
- Specify retention (from 1 day to 1 year)
  <br>
