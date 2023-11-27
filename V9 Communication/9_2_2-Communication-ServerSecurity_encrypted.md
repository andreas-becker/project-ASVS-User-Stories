# V9.2 Server Communication Security

## ASVS: 9.2.2

## ASVS Requirement description

Verify that encrypted communications such as TLS is used for all
inbound and outbound connections, including for management ports,
monitoring, authentication, API, or web service calls, database,
cloud, serverless, mainframe, external, and partner connections.
The server must not fall back to insecure or unencrypted protocols.

## User Story

**Feature_Name**: Encrypted Communications

**Story**:\
As a Security Engineer\
I want to use encrypted communications such as TLS for all inbound and outbound connections\
So that we can ensure secure communication and prevent fallback to insecure or unencrypted protocols

## Scenario

**Scenario_name**: Verifying the use of encrypted communications

**Gherkin syntax**:

```gherkin
Given our server's configuration
When I review the connections
Then all inbound and outbound connections should use encrypted communications such as TLS
And this should include management ports, monitoring, authentication, API, web service calls, database, cloud, serverless, mainframe, external, and partner connections
But the server should not fall back to insecure or unencrypted protocols
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/TLS_Cipher_String_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Pinning_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/319>
