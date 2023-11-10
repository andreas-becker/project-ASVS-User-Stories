# V10.3 Application Integrity

## ASVS: 10.3.3

## ASVS Requirement description

Verify that the application has protection from subdomain takeovers if the
application relies upon DNS entries or DNS subdomains, such as expired
domain names, out of date DNS pointers or CNAMEs, expired projects at
public source code repos, or transient cloud APIs, serverless functions, or
storage buckets (autogen-bucket-id.cloud.example.com) or similar.
Protections can include ensuring that DNS names used by applications are
regularly checked for expiry or change.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want to ...\
So that I ...

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

<https://cwe.mitre.org/data/definitions/350>
