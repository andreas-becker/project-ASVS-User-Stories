# V10.1 Code Integrity

## ASVS: 10.1.1

## ASVS Requirement description

Verify that a code analysis tool is in use that can detect
potentially malicious code, such as time functions, unsafe
file operations and network connections.

## User Story

**Feature_Name**: Code Analysis for Malicious Code

**Story**:\
As a Security Engineer\
I want to use a code analysis tool that can detect potentially malicious code\
So that we can ensure the security and integrity of our application
## Scenario

**Scenario_name**: Implementing Code Analysis Tool

**Gherkin syntax**:

```gherkin
Given our application's source code
When I run the code analysis tool
Then it should detect any potentially malicious code such as time functions, unsafe file operations, and network connections
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/749>
