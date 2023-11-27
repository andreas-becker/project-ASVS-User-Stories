# V1.14 Configuration Architecture

## ASVS: 1.14.6

## ASVS Requirement description

Verify the application does not use unsupported, insecure, or
deprecated client-side technologies such as NSAPI plugins, Flash,
Shockwave, ActiveX, Silverlight, NACL, or client-side Java applets.

## User Story

**Feature_Name**: Deprecated Technology Usage

**Story**:
As a Security Engineer\
I want to ensure that the application does not use unsupported, insecure, or deprecated client-side 
technologies\
So that we can maintain the security and integrity of our application

## Scenario

**Scenario_name**: Verifying non-usage of deprecated client-side technologies

**Gherkin syntax**:

```gherkin
Given our application's client-side technologies
When I review the technologies used
Then they should not include unsupported, insecure, or deprecated technologies such as NSAPI 
plugins, Flash, Shockwave, ActiveX, Silverlight, NACL, or client-side Java applets
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/477>