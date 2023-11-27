# V13.2 RESTful Web Service

## ASVS: 13.2.5

## ASVS Requirement description

Verify that REST services explicitly check the incoming
Content-Type to be the expected one, such as application/xml
or application/json.

## User Story

**Feature_Name**: REST Service Content-Type Validation

**Story**:\
As a Security Engineer\
I want the application to check the incoming Content-Type of REST services\
So that we can ensure the data received is in the expected format

## Scenario

**Scenario_name**: Checking Incoming Content-Type in REST Services

**Gherkin syntax**:

```gherkin
Given our application's REST services
When a request is received
Then the application should check the Content-Type of the request
And ensure it matches the expected type such as application/xml or application/json
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/REST_Assessment_Cheat_Sheet.html>\
<https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html>\
<https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html>\
<https://cwe.mitre.org/data/definitions/436>
