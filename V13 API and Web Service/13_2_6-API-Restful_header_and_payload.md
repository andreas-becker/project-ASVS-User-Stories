# V13.2 RESTful Web Service

## ASVS: 13.2.6

## ASVS Requirement description

Verify that the message headers and payload are trustworthy and
not modified in transit. Requiring strong encryption for transport
(TLS only) may be sufficient in many cases as it provides both 
confidentiality and integrity protection. Per-message digital 
signatures can provide additional assurance on top of the 
transport protections for high-security applications but bring
with them additional complexity and risks to weigh against the
benefits.

## User Story

**Feature_Name**: Ensuring Trustworthy Message Headers and Payload

**Story**:\
As a Security Engineer\
I want the application to verify the trustworthiness of message headers and payload\
So that we can ensure data integrity and confidentiality during transit.

## Scenario

**Scenario_name**: Checking Trustworthiness of Message Headers and Payload

**Gherkin syntax**:

```gherkin
Given our application's REST services
When a request is received
Then the application should verify the trustworthiness of message headers and payload
And ensure strong encryption for transport is used
And consider using digital signatures for high-security applications
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
<https://cwe.mitre.org/data/definitions/345>
