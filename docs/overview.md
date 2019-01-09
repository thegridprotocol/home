# Overview

## Scope
This document aims to provide background on:
- Why/how The Grid project came to be
- Its intended goals and values
- Differences with the Matrix protocol
- The high-level methodology/processes we want to put in place to ensure this protocol and project are successful
- The set of first priorities that will be worked on

## Origin
As independent developers on the Matrix protocol, we decided to pursue an alternative approach and set of goals and
provide a fresh set of eyes and solutions to the remaining challenges the protocol is trying to solve.

We have spent to this day over 18 months learning, analyzing and reverse-engineering the Matrix protocol, implemented
nearly all components with various use cases, granting us extensive knowledge about its:
- Strengths and weaknesses
- Current limitations
- Security vulnerabilities, both used and hypothetical

While we will like to take an alternate road from the Matrix protocol and become a stand-alone protocol, we believe in
the fundamental concepts and the building blocks and will keep The Grid protocol in line with those for the time being.

## Goals
The protocol will aim for the following goals:
- Solve the problem originally identified by the Matrix protocol, fragmented communications, engaging it from a social
  point of view.
- Simple client implementations, relying on the server for heavy lifting
- Federated communication between servers
- Decentralized data storage, spread across participating servers
- Designed for a full self-hostable stack to avoid centralization and/or monopoly

## Values
### Protocol
- Libre (Free) and Open protocol where its contributors and users are empowered
- Privacy of data and metadata
- Security of data and of the network
- Data exchange relying on a federated network, allowing everyone to spin-up a server and provide the service to a set of users
- Decentralized data storage, ensuring no single point of failure

### Management
- Transparency and openness around any talk, design session, workshop, meetings and any other related activity for the
  protocol, without secretive or confidential sessions
- Clear, understandable specification documents are the top priority and the main deliverable. A protocol is nothing
  without a specification.
- Taken actions and their consequences are used in evaluation, instead of intent.
- Decisions are backed with documented facts/feedback/issues

### Documentation
Documentation will be considered a generic term. Complexity, size, format and shape will be scoped to what is deemed
appropriate by the Governing Body for the various use cases.

As a protocol only exists in its specification and the only seeked resource, documentation will hold a special place for
this project and acts as the currency in spirit of the project, with various value depending on its complexity, size,
format, shape, use case and scope at hand.

It will also be used to enforce various good practices and force facts checking.
More details will be given in a separate, dedicated document to Documentation.

## The Grid vs Matrix
### Differences
#### Core values
Matrix’s ideals are Openness, Decentralization and Encryption [1](#links-and-sources) while The Grid’s ideals are
Freedom, Privacy and Security.

We see Matrix ideals as a subset of The Grid: While Matrix attempts to only solve the technical problem of fragmented
communications, The Grid wants to solve the problem at a social level, a higher level which includes the technical one.

While Matrix values and licenses align with the ideals of Open Source, The Grid would follow those of Libre (Free) software.
This would ensure that users and their rights are the focus and put at the center of each decision, instead of limiting
the discussion to technical matters only.

We believe in a social gain with The Grid protocol rather than technical or monetary gain, which should be reflected in
its own ecosystem.

#### Actors
Given the social purpose of the protocol, we believe involvement, participations and decision making should reflect the
social nature of the protocol.

Therefore, we want to put in place an ecosystem where anyone has a mean to express their opinion, provide feedback, or
contribute to the project itself. Making sure that no single entity is in a position of power alone. Instead, several
entities are in place to keep each other in check.

The creators of this protocol will initially stand alone in a position of power to bootstrap the ecosystem. Afterwards,
the newly-created non-profit will provide within its articles the requirements to join the various boards and decision
groups. See the Governing body section for more details.

#### Documentation
Matrix relies on reverse-engineering reference implementations since its creation 4 years ago, and has yet to produce a
version of its documentation that can be used to implement a full set of usable and interportable implementations.
A new spec proposal process was put in place but we believe it does not address the existing issues that led to the
current situation.

The Grid will therefore take a different approach and attempt to turn documentation into something positive and rewarding
for contributors and implementers, while putting processes and limits to avoid stagnation and status-quo.  
It will also take the approach that the spec (the end-result) is to be implemented by at least two projects, independent
of each other, to ensure that the documentation and the specification are not academic exercises, but real-world and
problem-solving.

This practical approach where contributors/implementers can see their work be used and recognized, is an example of a
rewarding experience for those who wish to contribute to the project.

### Which is better?
We don’t believe one is better than the other - The Grid and Matrix will each follow different values and a different
type of management.

While they will most likely solve technical problems in different ways, The Grid will initially build from what Matrix
is today and re-use existing and validated documentation. APIs like Client, Application services and Identity service
will remain compatible in the short term as the focus will be on producing a usable document that describes the server
protocol, which Matrix currently doesn’t have.

As The Grid and Matrix will both have concepts of Application Services and therefore Bridges, linking both protocols and
network will be a property that will be heavily leveraged on The Grid side to smooth out any transition or API change
that would make the two protocols otherwise incompatible and unable to exchange data.

If you believe in the same values and ideas as we do, we’ll be happy to have you help us with The Grid.

## Next steps
The high level steps are:
- Creation of a non-profit to kick-start, grow, foster and maintain The Grid protocol.
- Document all the concepts and network exchanges.
- Ensuring that at least two independent implementations validate the documentation.

### Governing body
To ensure the protocol is free of control from a single entity and that the users are empowered to control it, a non-profit
organisation will be created to represent the protocol lead and will be funded on donations.

This body will be created as soon as possible as we believe it is key to ensure neutrality in a communication protocol.

This governing body will be created using public and community-reviewed articles and will put in place technical board(s)
composed of key entities from the community to fulfill its mission.

This governing body will have for mission to ensure the protocol fostering and that its management values are respected
and followed.

Details about this controlling body, its missions and its proposed articles for creation are available in [a separate
document](governing-body.md).

### Initial Documentation
We recognize the hard work, effort and engineering level of the current Matrix protocol and wish to build on that,
instead of starting from scratch. We also believe that having a documentation of the as-is is key for people to contribute
constructively and avoid an unfair amount of work spent on reverse-engineering implementations to reach a level of
understanding sufficient to even start meaningful discussions/contributions to improve the protocol.

The biggest lack of documentation is currently the as-is for the server protocol, which deals with internal structures
of a Homeserver, the federation exchanges, the DAG model and its underlying algorithms. It is therefore not possible
to build on an existing documentation for those core concepts.

As the current federation protocol has several critical security vulnerabilities like state resets which have been used
in attacks [2](#links-and-sources) [3](#links-and-sources) on the live network, and very few underlying algorithms and
endpoints have been documented, we will take this opportunity to attempt creating internal structures and federation
exchanges that are immune to those known vulnerabilities, while holding back on any kind of optimization that would
require re-engineering on working, secure and tested concepts.

As all this will be done in the open, as per our core values, current issues to be addressed will be documented and
labeled appropriately so anyone in the community can offer a documented technical solution for them. We believe that
fresh sets of eyes and brains are required to solve those vulnerabilities.

Work has already been started on this and is currently being committed to this Github repository, and a generated online
version is also available. This work will be relocated under the newly The Grid organisation repositories very soon.

### Independent implementations
Meanwhile, we will encourage, foster and proactively seek that independent entities implement the protocol using its
latest documentation.

We believe that a communication protocol that does not have at least two independent implementations is fundamentally
dysfunctional, as its contributors and governing body have failed to communicate to or be understood by other parties
about its worth, merit and the related technical knowledge.

In the near and middle term, emphasis will be put on the various protocol efforts to not diverge too much too fast from
the Matrix protocol. Independent implementers will be able to easily and painlessly implement The Grid as well, ideally
in an invisible manner for the end user.

## Links and Sources
[1]: https://matrix.org/blog/home/ - “Support Matrix Today” section  
[2]: https://matrix.org/blog/2018/05/01/security-update-synapse-0-28-1/  
[3]: https://matrix.org/blog/2018/06/14/security-update-synapse-0-31-2/
