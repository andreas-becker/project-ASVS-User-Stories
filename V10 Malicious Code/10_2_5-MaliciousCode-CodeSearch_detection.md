# V10.2 Malicious Code Search

## ASVS: 10.2.5

## ASVS Requirement description

Verify that the application source code and third party
libraries do not contain malicious code, such as salami
attacks, logic bypasses, or logic bombs.

## User Story

**Feature_Name**: Malicious Code Detection

**Story**:\
As a Security Engineer\
I want to ensure that the application source code and third-party 
libraries do not contain malicious code, such as salami attacks, 
logic bypasses or logic bombs\
So that we can maintain the integrity of our application and 
protect it from potential threats

## Scenario

**Scenario_name**: Checking for Malicious Code in Libraries

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the code
Then it should not contain any malicious code, such as salami attacks, logic bypasses, or logic bombs
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/511>
