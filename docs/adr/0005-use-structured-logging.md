# Use structured logging

* Status: proposed
* Deciders: team

## Context and Problem Statement

Log lines are free text, so they are hard to search.

## Considered Options

* Plain text logs: simple, but hard to search.
* JSON logs: slightly harder to read, easy to search.

## Decision Outcome

Chosen option: JSON logs, because they can be searched by field.

### Consequences

* Developers need a log viewer to read them comfortably.
