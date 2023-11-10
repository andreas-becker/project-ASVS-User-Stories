# V14.5 HTTP Request Header Validation

## ASVS: 14.5.3

## ASVS Requirement description

Verify that the Cross-Origin Resource Sharing (CORS) Access-Control-AllowOrigin header uses a strict allow list of trusted domains and subdomains to match against and does not support the "null" origin.

## User Story

**Feature_Name**: Allow

**Story**:
As a Security Engineer\
I want to verify that CORS Access-Control-Allow-Origin header isn't * or null\
So that I'm specifying where I expect requests to come from

## Scenario

**Scenario_name**: Validate Access-Control-Allow-Origin isn't * or null

**Gherkin syntax**:

```gherkin
 Given an HTTP request
 And an Access-Control-Allow-Origin header
 When I receive the header
 Then I validate that it isn't `*`
    And I validate that it isn't `null`
```

## Validations

**Chef Inspec**
TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/346>
<https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Origin>
