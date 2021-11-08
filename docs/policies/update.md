# Service Update Policy

Last Updated: June 10, 2021

_We strive to frequently improve the service for all of our customers and to do so on a schedule and with processes that minimize the risk of disruption. However, we reserve the right to change the service at any time, including removing functionality. You may sometimes contract Ovation as your agent to configure the service or otherwise support your implementation and use of the service. Please refer to applicable statements-of-work and documents for policies regarding how we carry out such services; they are not covered here._

We provide a "production" instance of the service apart from a "sandbox" instance. You, often assisted by Ovation, can use sandbox to develop and test new or changing configurations and to preview upcoming releases. **Never put protected health information in sandbox because we do not restrict our internal access to it.**

All customers are hosted on these two instances. Your data is segregated from other customers' data. You cannot access theirs and they cannot access yours. Because the instances themselves are shared, any updates we make apply to everyone, but they will often have no noticeable impact on you because of your different configuration and workflow.

We sometimes update the service to improve capability and to fix defects. These updates can be modifications to our code or re-configuration of the cloud-based infrastructure upon which it relies.

In general, we tell you about upcoming updates and we update sandbox first so you can preview what's coming before it gets to production. The details depend on the type of update.

We do these types of updates:

- Maintenance updates (which occur weekly on a schedule)
- Critical fixes (which may happen at any time, averaging about once a week)
- Major release (planned individually and expected approximately twice yearly)

## Maintenance Updates

We update production every Sunday between 6PM and 8PM Eastern Time. We update sandbox with the same changes Thursday night and send you a link to a description of the changes on Friday morning. (Contact support@ovation.io to confirm or update the email recipients for your organization.)

| Day of Week | Time (ET) | Update Step              |
| ----------- | --------- | ------------------------ |
| Thursday    | 6PM-8PM   | Update sandbox           |
| Friday      | 9AM-12PM  | Distribute release notes |
| Sunday      | 6PM-8PM   | Update production        |

The service remains available during most updates and users are rarely affected while the updates are ongoing, the most common impact being minor performance degradation. Sometimes, however, we prohibit use in order to apply certain kinds of updates. We intend to notify you at least 48 hours in advance in those cases and we will work hard to minimize the frequency and length of such system unavailability.

We strive to avoid impacting your users with the changes in a Maintenance Update. We avoid changes that would modify the workflow for an end-user (although we are more liberal about the impact on administrative use). Most significant changes appear only when we reveal them at your request ("feature flags") or when you do (via an administrative option or new access you can grant).

In rare cases we cannot update sandbox separate from production because of a small amount of shared infrastructure. For example, in order for your credentials to get you into both sandbox and production, we have to use the same system for both. Therefore, when we update this system, both sandbox and production are updated simultaneously.

All changes in a Maintenance Update are approved and tested, as is the update as a whole. Please see Change Control and Testing below.

## Critical Fixes

Whenever practical, we defer fixes to a Maintenance Update but we will occasionally apply critical changes outside of the Maintenance Update schedule. This happens about once a week.

We will not usually notify you about these updates and, depending on their urgency, they may not be applied to sandbox before production.

Critical Fixes undergo an extra quality check and require documented and approved justification for their accelerated delivery.

## Major Releases

We sometimes apply updates that significantly modify the service's capabilities or user interface. Since, unlike with Maintenance Updates, these changes can disrupt end-user workflows, we give at least a month's notice and update sandbox at least two weeks before updating production. You will know the plan for a Major Release long before it impacts your users in production. We anticipate about two Major Releases each year.

## Change Control and Testing

We have strict change control policies for each change to our code, for each update we apply to the service and for changes to our operational infrastructure.

Code changes are tracked in a change management system, must be approved by an authorized person who did not implement the change and must be tested by another engineer who did not implement the change. Each service update must then itself be approved and must pass regression testing. Any direct changes to the infrastructure are also tracked in the change management system and can only be done by limited, authorized staff.

_If you have questions or concerns about this policy, you can contact us via email at <a href="mailto:support@ovation.io">support@ovation.io</a>._
