# ASVS Requirement: V2.2.3

## ASVS:.2.2.3

## ASVS Requirement description

Verify that secure notifications are sent to users after updates to authentication details, such as credential resets, email or address changes, logging in from unknown or risky locations. The use of push notifications - rather than SMS or email - is preferred, but in the absence of push notifications, SMS or email is acceptable as long as no sensitive information is disclosed in the notification.

## User Story

**Feature_Name**: Limit the use of weak authenticators

**Story**:
As a Security Engineer\
I want to use weak authenticators (such as SMS and email) only as secondary verification and transaction approval,
so that my system is protected with more secure authentication methods.

## Scenario

**Scenario_name**: Enable secure notification on authentication details change

**Gherkin syntax**:

```gherkin
Given a capability for users to change their authentication details
When those changes are submitted
Then I trigger a push notification, or if unavailable an SMS or email, to the user notifying them of the event
```

`authentication details` can be credential resets, email or address changes

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html> \
<hhttps://cwe.mitre.org/data/definitions/521.html>
