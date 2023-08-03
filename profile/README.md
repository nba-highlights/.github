# NBA Highlights
The purpose of this organisation is to automatically create NBA Highlight Videos.

# Service Interaction
The diagram below shows the envisioned interaction between the various services. It heavily relies on AWS events for:

1. loose coupling between services.
1. improved scalability of individual services.
1. easy testing of individual services.
1. reduced code footprint (we only need to write HTTP endpoints for our services).

![messaging-architecture](/profile/doc/nba-highlights-messaging-architecture.svg)
