# V14.5 HTTP Request Header Validation

## ASVS: 14.5.4

## ASVS Requirement description

Verify that HTTP headers added by a trusted proxy or SSO devices,
such as a bearer token, are authenticated by the application.

## User Story

**Feature_Name**: HTTP Header Validation

**Story**:
As a Security Engineer\
I want to ensure that HTTP headers added by a trusted proxy or Single Sign-On (SSO) devices, such
as a bearer token, are authenticated by the application\
So that we can maintain the security and integrity of our application

## Scenario

**Scenario_name**: Validating HTTP Headers

**Gherkin syntax**:

```gherkin
Given an HTTP request with headers added by a trusted proxy or SSO devices
When the application receives the request
Then it should authenticate the headers
And reject the request if the headers are not authenticated
```

## Validations

**Chef Inspec**
TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/306>
<https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Origin>
