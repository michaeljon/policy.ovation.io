# Service Availability Policy

Last Updated: June 10, 2021

Please see our [Service Update Policy](update.md) for information about when and how we update our service, including when these updates may involve planned service unavailability.

Our goal is to limit the time that the service is effectively unavailable to less than 2 hours a month, whether or not the unavailability was unplanned (99.75% uptime). We consider the service to be effectively unavailable if any of these are true for more than 5 minutes

- More than 25% of attempts to access the service fail
- Performance degrades at least 10x for more than 25% of user actions
- One cannot execute this basic LIMS workflow, regardless of configuration: create order -> receive sample -> complete test workflow -> approve and deliver patient results report

In such a case, or in the event that our service is impaired in some meaningful way, but not effectively unavailable, we will communicate the situation and our response via [status.ovation.io](https://status.ovation.io). You can subscribe there to receive these updates.

Resolving production incidents sometimes involves making service updates, for which we will follow the policies described in our Service Update Policy.

You can request a formal incident report after a production incident from <a href="mailto:support@ovation.io">support@ovation.io</a>.

_If you have questions or concerns about this policy, you can contact us via email at <a href="mailto:support@ovation.io">support@ovation.io</a>._
