# 13 - QUIZ 2 - IDENTITY & ACCESS MANAGEMENT

## SECTION 02 - IDENTITY ACCESS MANAGEMENT <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/28/2023 <br>

### 06/06/2024 : Reviewed <br>
<br>

### QUESTION 1 >>

<details>
    <summary>
    What is the correct definition of IAM Roles?
      - An IAM entity that defines a set of permissions for making AWS service requests, that will be used by AWS services
      - IAM Users in multiple Groups
      - A password policy
      - Permissions assigned to Users to perform actions
    </summary>
  Some AWS services will need to perform actions on your behalf. To do so, you must assign permissions to services with IAM Roles  
</details>

<br>

### QUESTION 2 >>

<details>
  <summary>
  Which of the following is an IAM Security Tool?
    - IAM Credentials Report
    - IAM Root Account Manager
    - IAM Services Report
    - IAM Security Advisor
  </summary>
  IAM Credentials report lists all your account's user and the status of their various credentials. The other IAM Security Tool is IAM Access Advisor. It shows the service permissions granted to a user and when those services were last accessed.
</details>

<br>

### QUESTION 3 >>

<details>
        <summary>
        Which answer is INCORRECT regarding IAM Users?
          - IAM Users can belong to multiple groups
          - IAM Users don't have to belong to a group
          - IAM Users can have policies assigned to them
          - IAM Users access AWS with the root account credentials
        </summary>
      IAM Users access AWS using a username and a password
</details>

<br>

### QUESTION 4 >>

<details>
        <summary>
        Which of the following is an IAM best practice?
          - Don't use the root user account
          - Create several users for a physical person
          - Share credentials so a colleague can perform a task for you
          - Do not enable MFA for easier access
        </summary>
      You only want to use the root account to create your first IAM user, and for a few account and service management tasks. For every day and administration tasks, use an IAM user with permissions.
         
</details>

<br>

### QUESTION 5 >>

<details>
        <summary>
        What are IAM Policies?
          - AWS services performable actions
          - JSON documents to define Users, Groups or Roles' permissions
          - Rules to set up a password for IAM Users
        </summary>
      An IAM policy is an entity that, when attached to an identity or resource, defines their permissions
         
</details>

<br>

### QUESTION 6 >>

<details>
        <summary>
        Under the shared responsibility model, what is the customer responsible for in IAM?
          - Infrastructure security
          - Compliance validation
          - Configuration and vulnerability analysis
          - Assigning users proper IAM Policies
        </summary>
      Customers are responsible for defining and using IAM policies
         
</details>

<br>

### QUESTION 7 >>

<details>
        <summary>
        Which of the following statements is TRUE?
        - The AWS CLI can interact with AWS using commands in your command-line shell, while the AWS SDK can interact with AWS programmatically
        - The AWS SDK can interact with AWS using commands in your command-line shell, while the AWS CLI can interact with AWS programatically
        </summary>
      The AWS CLI interacts with the command line shell on your computer, while the SDK interacts programmatically
         
</details>

<br>

### QUESTION 8 >>

<details>
        <summary>
        Which principle should apply regarding IAM Permissions?
          - Grant most privilege
          - Grant least privilege
          - Grant permissions if your employee asks you to
          - Restrict root account permissions
        </summary>
      The rule of thumb is to grant the LEAST permissions possible a user will need (for security reasons). This extends further in that services a user doesn't use should be removed from their permissions (can be view on the user/permissions page)
         
</details>

<br>

### QUESTION 9 >>

<details>
        <summary>
        What should you do to increas eyour root account security?
          - Enable Multi-Factor Authentication (MFA)
          - Remove permissions from the root account
          - Use AWS only through the Command Line Interface (CLI)
        </summary>
      You want to enable MFA in order to add a layer of security, so even if your password is stolen, lost or hacked your account is not compromised
         
</details>

<br>
