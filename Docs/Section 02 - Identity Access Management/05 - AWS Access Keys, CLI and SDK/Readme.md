# 05 - AWS ACCESS KEYS, CLI & SDK

## SECTION 02 - IDENTITY ACCESS MANAGEMENT <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/28/2023 <br>

### 05/28/2024 - Reviewed

<br>

### HOW CAN USERS ACCESS AWS >>

To access AWS, you have three options:

- AWS Management Console (protected by password + MFA)
- AWS Command Line Interface (CLI): protected by access keys
- AWS Software Developer Kit (SDK) - for code: protected by access keys

<br>

Access Keys are generated through the AWS Console

<br>

Users manage their own access keys

<br>

Acces Keys are secret, just like a password. Don't share them

- Access Key ID ~= username
- Secret Access Key ~= password

### WHAT'S THE AWS CLI >>

A tool that enables you to interact AWS services using commands in your command-line shell

<br>

Direct access to the public API of AWS services

<br>

You can develop scripts to manage your resources

<br>

It's open-source: [Github AWS CLI](https://github.com/aws/aws-cli)

<br>

Alternative to using AWS Management Console

<br>

### WHAT IS THE AWS SDK? >>

[AWS Software Development Kit](https://aws.amazon.com/sdk-for-javascript/) (AWS SDK)

Language-specific APIs (set of libraries)

Enables you to access and manage AWS services programmatically

Embedded within your application

Supports

- SDKs (JavaScript, Python, PHP, .NET, Ruby, Java, Go, Node.js, C++)
- Mobile SDKs (Android, iOS...)
- IoT Device SDKs (Embedded C, Arduino...)

Example: AWS CLI is built on AWS SDK for Python

<br>
