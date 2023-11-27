# V6.1 Data Classification

## ASVS: 6.1.2

## ASVS Requirement description

Verify that regulated health data is stored encrypted while at
rest, such as medical records, medical device details, or
de-anonymized research records.

## User Story

**Feature_Name**: Secure Health Data Storage

**Story**:\
As a Security Engineer\
I want to ensure that regulated health data such as medical records, medical device details,
or de-anonymized research records, is stored encrypted while at rest\
So that we can maintain the confidentiality and integrity of our sensitive health data

## Scenario

**Scenario_name**: Verifying encryption of health data at rest

**Gherkin syntax**:

```gherkin
Given our application's storage of regulated health data
When I review the storage method
Then the health data should be encrypted while at rest
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
