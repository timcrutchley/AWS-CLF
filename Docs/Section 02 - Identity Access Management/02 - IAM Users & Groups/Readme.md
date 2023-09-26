# 02 - IAM USERS & GROUPS

## SECTION 02 - IDENTITY ACCESS MANAGEMENT <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/26/2023 <br>

<br>

### ROOT USER VS IAM USER >>

Root user is not intended for regular use. Instead, an admin user should be created. This difference can be noted when logging in (login as root)
<br>

### CREATE IAM ADMIN USER >>

Go to the **IAM dashboard**. This can be done by manuaully navigating to that section or by searching 'IAM' in the search bar

1. Create User
2. Fill out username
3. Give access to AWS Management Console (checked)
4. For the first time, create a 'IAM user' instead of 'Identity Center'
5. Create a custom password (should be auto-generated for other users)
6. Disable 'users must create a new user on sign in' (should be enabled for other users)
   <br>

### CREATE GROUP >>

1. Click 'Create Group' button
2. Call the group 'admin'
3. Attach 'AdministratorAccess' policy
4. Click 'Create User Group' button

<br>

### ASSIGN USER TO GROUP >>

1. After creating user group it will take back to permission options
2. Under user groups, check the newly created 'admin' group
3. Click 'Next' button (scroll down if not seen)
4. Set a tag if necessary (Such as 'Department' 'Engineering')
5. Click 'Create user' button
6. From here, can email sign-in instructions, download .csv file
7. Click 'return to users list' button
8. Back at the dashboard, click 'user groups'
9. Click 'admin'
10. The new user should be listed as a user in the group
    <br>

### CREATE ALIAS >>

1. From the IAM dashboard, on the right where the account ID# is, click 'Create Alias'.
2. Create a unique alias
3. Copy the login link
4. Past in incognito window or another browser
5. Login with the aim username/pass
6. Keep both the root user & IAM user account open
   <br>
