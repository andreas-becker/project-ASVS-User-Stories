# V5.2 Sanitization and Sandboxing

## ASVS: 5.2.7

## ASVS Requirement description

Verify that the application sanitizes, disables, or sandboxes
user-supplied Scalable Vector Graphics (SVG) scriptable content,
especially as they relate to XSS resulting from inline scripts,
and foreignObject.

## User Story

**Feature_Name**: Safeguarding User-Supplied SVG Content

**Story**:\
As a Security Engineer\
I want to ensure that the application properly handles user-supplied Scalable 
Vector Graphics (SVG) content\
So that we can prevent unauthorized changes that could compromise the
application's security

## Scenario

**Scenario_name**: Validation of untrusted data or HTTP file metadata

**Gherkin syntax**:

```gherkin
TBD
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/DOM_based_XSS_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/918>
