# V1.5 Input and Output Architecture

## ASVS: 1.5.2

## ASVS Requirement description

Verify that serialization is not used when communicating with
untrusted clients. If this is not possible, ensure that adequate
integrity controls (and possibly encryption if sensitive data is
sent) are enforced to prevent deserialization attacks including
object injection.

## User Story

**Feature_Name**: Prevent Deserialization Attacks

**Story**:
As a Security Engineer\
I want to ensure that serialization is not used when communicating with untrusted clients\
So that we can prevent deserialization attacks including object injection and maintain the
integrity and confidentiality of our data

## Scenario

**Scenario_name**: Implementing adequate integrity controls to prevent deserialization attacks

**Gherkin syntax**:

```gherkin
Given our application's communication processes with untrusted clients
When I implement adequate integrity controls and possibly encryption if sensitive data is sent
Then deserialization attacks including object injection are prevented
And the integrity and confidentiality of our data is maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/502>