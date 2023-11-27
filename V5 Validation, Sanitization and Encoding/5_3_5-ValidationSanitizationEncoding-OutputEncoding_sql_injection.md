# V5.3 Output Encoding and Injection Prevention

## ASVS: 5.3.5

## ASVS Requirement description

Verify that where parameterized or safer mechanisms are not
present, context-specific output encoding is used to protect
against injection attacks, such as the use of SQL escaping to
protect against SQL injection.

## User Story

**Feature_Name**: Using Safe Encoding Techniques

**Story**:\
As a Security Engineer\
I want to ensure that when safer mechanisms are not available, the application
uses safe encoding techniques to protect against injection attacks\
So that we can keep our data safe and secure

## Scenario

**Scenario_name**: TBD

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

<https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/DOM_based_XSS_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/HTML5_Security_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Injection_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Injection_Prevention_in_Java_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/LDAP_Injection_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/OS_Command_Injection_Defense_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/File_Upload_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Query_Parameterization_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Bean_Validation_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/XML_External_Entity_Prevention_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/XML_Security_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/89>
