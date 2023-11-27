# V2.10 Service Authentication

## ASVS: 2.10.2

## ASVS Requirement description

Verify that if passwords are required for service authentication,
the service account used is not a default credential. (e.g.
root/root or admin/admin are default in some services during
installation).\
_The use of an HSM is recommended for password storage_

## User Story

**Feature_Name**: Avoid Default Service Credentials

**Story**:
As a Security Engineer\
I want to ensure that service authentication does not rely on default credentials\
So that we can prevent unauthorized access and maintain the security of our system

## Scenario

**Scenario_name**: Verifying non-usage of default service credentials

**Gherkin syntax**:

```gherkin
Given our system's service authentication process
When I review the credentials used
Then they should not be default credentials such as root/root or admin/admin
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
<https://cwe.mitre.org/data/definitions/255>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.1

