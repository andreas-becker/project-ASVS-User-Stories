# V6.1 Data Classification

## ASVS: 6.1.1

## ASVS Requirement description

Verify that regulated private data is stored encrypted while at
rest, such as Personally Identifiable Information (PII), sensitive
personal information, or data assessed likely to be subject to
EU's GDPR.

## User Story

**Feature_Name**: Secure Storage of Private Data

**Story**:\
As a Security Engineer\
I want to ensure that regulated private data such as Personally Identifiable Information (PII),
sensitive personal information, or data likely to be subject to EU's GDPR, is stored encrypted
while at rest\
So that we can maintain the confidentiality and integrity of our sensitive data

## Scenario

**Scenario_name**: Verifying encryption of private data at rest

**Gherkin syntax**:

```gherkin
Given our application's storage of regulated private data
When I review the storage method
Then the private data should be encrypted while at rest
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/311>
