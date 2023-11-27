# V10.2 Malicious Code Search

## ASVS: 10.2.3

## ASVS Requirement description

Verify that the application source code and third party
libraries do not contain back doors, such as hard-coded
or additional undocumented accounts or keys, code
obfuscation, undocumented binary blobs, rootkits or 
anti-debugging, insecure debugging features or otherwise
out of date, insecure or hidden functionality that could 
be used maliciously if discovered.

## User Story

**Feature_Name**: No Backdoors in Code

**Story**:\
As a Security Engineer\
I want to ensure that the application source code and third-party
libraries do not contain backdoors, such as hard-coded or additional
undocumented accounts or keys, code obfuscation, undocumented binary
blobs, rootkits, or anti-debugging\
So that we can prevent any hidden functionality that could be used
maliciously if discovered

## Scenario

**Scenario_name**: Checking for Backdoors in Code

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the code
Then it should not contain any backdoors, such as hard-coded or additional undocumented accounts or keys, code obfuscation, undocumented binary blobs, rootkits, or anti-debugging
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/507>
