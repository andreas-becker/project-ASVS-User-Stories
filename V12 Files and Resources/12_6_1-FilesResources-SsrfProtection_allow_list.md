# V12.6 SSRF Protection

## ASVS: 12.6.1

## ASVS Requirement description

Verify that the web or application server is configured with an
allow list of resources or systems to which the server can send
requests or load data/files from.

## User Story

**Feature_Name**: SSRF Protection

**Story**:\
As a Security Engineer\
I want applications to speak to whitelisted destinations\
So that the application is less prone to Server-side request forgery attacks

## Scenario

**Scenario_name**: Whitelisted request destinations

**Gherkin syntax**:

```gherkin
GIVEN a whitelist of resources and systems an application can send requests is configured
WHEN a request is made by the application to a destination not in the whitelist
THEN the request is dropped
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/918>
