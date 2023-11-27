# V8.1 General Data Protection

## ASVS: 8.1.4

## ASVS Requirement description

Verify the application can detect and alert on abnormal numbers of
requests, such as by IP, user, total per hour or day, or whatever
makes sense for the application.

## User Story

**Feature_Name**: Abnormal Request Detection

**Story**:\
As a Security Engineer\
I want the application to detect and alert on abnormal numbers of requests\
So that we can monitor and respond to potential security incidents effectively

## Scenario

**Scenario_name**: Verifying Abnormal Request Detection

**Gherkin syntax**:

```gherkin
Given our application's request handling system
When I review the request logs
Then it should show alerts for abnormal numbers of requests
And it should consider factors such as IP, user, total per hour or day
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/770>
