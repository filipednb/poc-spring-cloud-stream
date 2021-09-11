#Spring Cloud Stream POC

Event Driven Architecture is a software architecture paradigm promoting
the production, detection, consumption of and reactions to events.

## Communication and distribution
- Events don't move, they occur
- Often relies on network-based systems to communicate events

## Representation

- Events should carry enough information for the event consumer to act on it
So events should have 2 information: Payload and Headers.
You can hear about 'Events' and 'messages' over there, and they are the same.
    - Event payload
    - Event meta-data (time, id, source, type, etc)
    