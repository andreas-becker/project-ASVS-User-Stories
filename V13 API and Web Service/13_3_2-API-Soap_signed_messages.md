## V13.3 SOAP Web Service

## ASVS: 13.3.2

## ASVS Requirement description

Verify that the message payload is signed using WS-Security to
ensure reliable transport between client and service.

## User Story

**Feature_Name**: Reliable Transport with WS-Security

**Story**:\
As a Security Engineer\
I want the message payload to be signed using WS-Security\
So that we can ensure reliable transport between the client and the service

## Scenario

**Scenario_name**: Ensuring Reliable Transport with WS-Security

**Gherkin syntax**:

```gherkin
Given our application's SOAP Web Service
When a message payload is sent
Then the application should sign the payload using WS-Security
And this should ensure reliable transport between the client and the service
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/XML_Security_Cheat_Sheet.html>\
<https://cwe.mitre.org/data/definitions/345>
