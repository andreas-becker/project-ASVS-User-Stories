# V4.3 Other Access Control Considerations

## ASVS: 4.3.3

## ASVS Requirement description

Verify the application has additional authorization (such as step
up or adaptive authentication) for lower value systems, and / or
segregation of duties for high value applications to enforce
anti-fraud controls as per the risk of application and past fraud.

## User Story

**Feature_Name**: Enhanced Authorization Control

**Story**:
As a Security Engineer\
I want to  implement additional authorization measures such as step up or adaptive authentication 
for systems of lower value, and segregation of duties for high value applications\
So that we can enforce anti-fraud controls based on the risk of the application and past fraud
incidents

## Scenario

**Scenario_name**: Implementing Enhanced Authorization Controls

**Gherkin syntax**:

```gherkin
Given our application's authorization process
When I review the controls for systems of lower and higher value
Then lower value systems should have additional authorization measures such as step up or adaptive authentication
And high value applications should have segregation of duties
And these controls should enforce anti-fraud measures based on the risk of the application and past fraud incidents
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Access_Control_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/732>

