# V2.10 Service Authentication

## ASVS: 2.10.3

## ASVS Requirement description

Verify that passwords are stored with sufficient protection to 
prevent offline recovery attacks, including local system access.\
_The use of an HSM is recommended for password storage_

## User Story

**Feature_Name**: Secure Password Storage

**Story**:
As a Security Engineer\
I want to ensure that passwords are stored with sufficient protection\
So that we can prevent offline recovery attacks, including local system access

## Scenario

**Scenario_name**: Verifying secure storage of passwords

**Gherkin syntax**:

```gherkin
Given our system's service authentication process
When I review the password storage method
Then it should provide sufficient protection to prevent offline recovery attacks, including local
system access
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/522>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.1

