# V6.1 Data Classification

## ASVS: 6.1.3

## ASVS Requirement description

Verify that regulated financial data is stored encrypted while at
rest, such as financial accounts, defaults or credit history, tax
records, pay history, beneficiaries, or de-anonymized market or 
research records.

## User Story

**Feature_Name**: Secure Financial Data Storage

**Story**:\
As a Security Engineer\
I want to ensure that regulated financial data such as financial accounts, credit history,
tax records, pay history, beneficiaries, or de-anonymized market or research records,
is stored encrypted while at rest\
So that we can maintain the confidentiality and integrity of our sensitive financial data

## Scenario

**Scenario_name**: Verifying encryption of financial data at rest

**Gherkin syntax**:

```gherkin
Given our application's storage of regulated financial data
When I review the storage method
Then the financial data should be encrypted while at rest
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
