# V2.10 Service Authentication

## ASVS: 2.10.4

## ASVS Requirement description

Verify passwords, integrations with databases and third-party
systems, seeds and internal secrets, and API keys are managed
securely and not included in the source code or stored within
source code repositories. Such storage SHOULD resist offline
attacks.\
_The use of an HSM is recommended for password storage_

## User Story

**Feature_Name**: Secure Management of Passwords and Secrets

**Story**:
As a Security Engineer\
I want to ensure that passwords, database integrations, third-party system integrations, seeds,
internal secrets and API keys are managed securely and that they are not included in the source
code or stored within source code repositories\
So that we can prevent offline attacks and maintain the security of our system

## Scenario

**Scenario_name**: Verifying secure management of passwords and secrets

**Gherkin syntax**:

```gherkin
Given our system's service authentication process
When I review the management of passwords, database integrations, third-party system integrations, seeds, internal secrets, and API keys
Then they should not be included in the source code or stored within source code repositories
And their storage should resist offline attacks
And the use of an HSM should be considered for password storage
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
<https://cwe.mitre.org/data/definitions/798>

