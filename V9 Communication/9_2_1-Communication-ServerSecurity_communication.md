# V9.2 Server Communication Security

## ASVS: 9.2.1

## ASVS Requirement description

Verify that connections to and from the server use trusted TLS
certificates. Where internally generated or self-signed
certificates are used, the server must be configured to only trust
specific internal CAs and specific self-signed certificates. All
others should be rejected.

## User Story

**Feature_Name**: Server Communication Security

**Story**:\
As a Security Engineer\
I want to use trusted TLS certificates for server connections\
So that we can ensure secure communication

## Scenario

**Scenario_name**: Verifying the use of trusted TLS certificates

**Gherkin syntax**:

```gherkin
Given our server's configuration
When I review the TLS certificates used for connections
Then it should use trusted TLS certificates
And when internally generated or self-signed certificates are used
Then the server should be configured to trust specific internal CAs and specific self-signed certificates
But it should reject all other certificates
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
<https://cwe.mitre.org/data/definitions/295>
