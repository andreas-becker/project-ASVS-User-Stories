# V6.3 Random Values

## ASVS: 6.3.3

## ASVS Requirement description

Verify that random numbers are created with proper entropy
even when the application is under heavy load, or that the
application degrades gracefully in such circumstances.

## User Story

**Feature_Name**: Secure Random Number Generation

**Story**:\
As a Security Engineer\
I want to ensure that our application generates random numbers 
with proper entropy, even under heavy load\
So that we can maintain the security of our operations and data
and ensure the application's performance remains stable

## Scenario

**Scenario_name**: Ensuring Secure Random Number Generation

**Gherkin syntax**:

```gherkin
Given our application's generation of random numbers
When the application is under heavy load
Then it should still generate numbers with proper entropy
And if it cannot, the application should degrade gracefully
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/338>
