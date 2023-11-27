# V6.2 Algorithms

## ASVS: 6.2.5

## ASVS Requirement description

Verify that known insecure block modes (i.e. ECB, etc.), padding
modes (i.e. PKCS#1 v1.5, etc.), ciphers with small block sizes
(i.e. Triple-DES, Blowfish, etc.), and weak hashing algorithms
(i.e. MD5, SHA1, etc.) are not used unless required for backwards
compatibility.

## User Story

**Feature_Name**: Avoidance of Insecure Cryptographic Elements 

**Story**:\
As a Security Engineer\
I want to ensure that our application does not use known insecure block modes, padding modes, 
ciphers with small block sizes, and weak hashing algorithms, unless required for backwards 
compatibility\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying non-usage of insecure cryptographic elements

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When I review the block modes, padding modes, ciphers, and hashing algorithms used
Then they should not include known insecure elements such as ECB block mode, PKCS#1 v1.5 padding mode, Triple-DES or Blowfish ciphers, or MD5 or SHA1 hashing algorithms
Unless these insecure elements are required for backwards compatibility
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/326>
