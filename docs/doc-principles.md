# Documentation Principles

## Scope
This document aims to:
- Define the value and importance of documentation for the protocol and in the ecosystem
- Define key terms
- Describe the principles of Documentation processes
- Describe the various types of Documentation

## Concepts
We strongly believe in documentation, not because of the documentation itself, but because of what it represents, the
values it upholds and a possibly near universal recognition of worth for the knowledge it contains.

The rest of this document will describe those in details.

### Proof of Work
The expression ***Proof of Work***, shortened to ***PoW***, will be used throughout this document to represent the effort
made by someone to articulate and communicate meaningfully about relevant matters towards others. It comes from the
[Proof-of-work system](https://en.wikipedia.org/wiki/Proof-of-work_system).

There is no restriction on the amount of work itself, which can range from near-to-nothing to extensive amounts of time
and money. It will directly depend on the situation and the goal of the debate.

Anyone in the community (including from the boards) who wants to participate in a debate MUST produce ***PoW***.  
***PoW*** does not mean minimal amount of knowledge. Rather, ***PoW*** means minimal amount of effort.  
We expect back-and-forth argumentation backed by ***PoW*** as people participate in an exchange of some sort, until no
more argumentation can be brought up, which will settle that particular exchange.

### Documentation
The word ***Documentation*** will be used as a generic concept throughout this document.  
Any document that seeks to be recognized as *Documentation* must incorporate at least one ***PoW***.

It is defined as something that:
- Is available publicly
- Is directly reachable using a [URL](https://en.wikipedia.org/wiki/URL)
- Is a standalone piece of work, or directly incorporated in one at the same location
- Is written in English if text-based
- Incorporates at least one ***PoW*** from the concepts below
- Can be re-used by others to build on
- Provides a publicly accessible channel for feedback

Examples of Documentation:
- A standalone HTML page
- A PDF document
- An [ODT](https://en.wikipedia.org/wiki/OpenDocument) document
- A Gogs/Gitea/Github/Gitlab issue
- A comment on an issue
- A Cryptpad document
- A Google Docs document
- A schematic wireframe
- A fully rendered and styled visual mockup of a GUI

Any produced *Documentation* is guaranteed to be reviewed by the governing body in a timely fashion. *Documentation* will
therefore become the ideological currency of the project and ensure everyone who worked to produce one will be able to
"trade" it for something else (e.g. trade it for the review of the documentation).

We make no generic requirements on the format, length or overall wording of *Documentation*, as long as the vast majority
of the community is happy about it. This is on purpose, following on the issues met so far using a too strict proposal
process and we’ll rely on a naturally occurring balance with gentle nudges in the right direction.

The Technical Board will produce a list of officially recommended formats, way of sharing and provide sample templates
for the various fitting use case so people can easily get started. Those will be kept up to date and relevant.

### Implementation
The term ***Implementation*** will refer to the deliverable or the actual product derived from a given *Documentation*.
It is a generic term, it's meaning will change depending on the role/occupation of the deliverer.

Examples of Implementation:
- As a software developer: source code
- As a graphic designer: Wireframes and mockups
- As a User Experience engineer: Guidelines/recommendations
- As a system administrator: Install guides, deployment scripts, etc.

## High-level concepts
To ensure successful *Documentation*, it is essential to respect some core concepts that reflect the value of the protocol,
its openness and the recognition of ***PoW***.

The following concepts are how something will be judged as qualifying as a ***PoW***.

### Extract, organize and materialize thoughts
Our experience shows that the human mind tends to underestimate risks, difficulty level and overall workload.
Therefore we believe that the act of writing the *Documentation* - regardless how small - simply forces one to think further
and in more details about what one tries to accomplish and filters the most basic and unconscious biases.

### State functional problem to be solved
While chat or voice exchanges are good for quick exchanges, it’s easy to lose sight of the actual problem one is trying
to solve and the involved scope, or simply not really know what problem is currently be solved. By stating up front the
problem, the scope is set and can be enforced in further exchanges.

### Facts backing
**This is *Proof of Work***

As this is a technical exercise, it is important that any statement that influences choices, like "it is very likely that
X happens", be backed up by objective, quantifiable and/or qualifiable facts from an independent source.

### Usage feedback and usability
**This is *Proof of Work***

Using or testing software/*Documentation* or any kind of item that comes from a ***PoW*** becomes itself a ***PoW*** once
that experience is documented.

This is typically:
- Software tests in development cycle
- Daily usage from end-users
- Bug reports of software of the protocol specification itself
- Feature request from end-users

In addition to load testing, pen-testing, etc, usability focus groups (whether remote or in person), feedback via surveys
and suggestion forms provide an excellent opportunity to gain new and sometimes  unexpected insights. If the same
feature request or complaint appears frequently, it should be considered actionable. Putting together such a compiled
list or results of testing provides actionable next steps.

Ad hoc observations such as “my group found this feature difficult to use” can be logged as an issue and may also be
considered; however compiling quantitative evidence (X% of users could not complete an assigned task) is strongly encouraged.

UX professionals and designers should also be encouraged to submit wireframes, mockups, and process documentation
for future functionality. (Not just "what’s broken?" but "what can be dreamed and built?").
In this instance, a well-developed use case is considered ***PoW***.

### Sources linking
**This is a *Proof of Work***.

As facts must come from external sources, it is critical to include links to those sources, so anyone evaluating the
document can have access to the same information as the author without having to research the data themselves.

### Proposed solution
**This is a *Proof of Work***.

Once the problem to be solved and the scope are documented, one will describe the proposed solution that solves the
stated problem/issue.  
Next to the description of the solution, one MUST reiterate in a short conclusion how the solution effectively solves
the problem.

### Rationalisation
**This is a *Proof of Work***.

As one goes through the proposed solution, one will use the various facts and/or linked sources to justify the proposed
solution. One CANNOT rely on common knowledge, as this is a cognitive bias. On the other hand, one is free to rely on
required knowledge.

Example: If describing an HTTP endpoint, one may have to justify the validity of the HTTP choices made (POST vs PUT, etc.),
but one will not have to justify TCP principles.

### Implementation
**This is a *Proof of Work***.

This validates the proposed solution with an actual Implementation and ensures that the theoretical outcome is feasible
in practice, as a real product for real users.

### Peer convincing
**This is a *Proof of Work***.

Proposals should be written in a way that one attempts to convince others that the proposed solution is the correct one,
instead leaving the fact checking work to their reviewing peers.  
One MUST NOT assume they are correct to start with. They MUST convince others of the validity of their claims using the
elements described above.  
It MUST be easier to read the proposal than to write it.

## Types
*Documentation* will be divided into several types, each having their own requirements and goals.  
Except for The Protocol Specification, any of those *Documentation* can be put forward by the governing body or by the
community.

Types are not mutually exclusive and a single *Documentation* can be of several types.

The various types will outline the various stages/steps of the overall process which is a recurring cycle:
1. Guides/Recommendations/Templates and The Protocol Specification allow Implementations to be made
2. Implementations trigger Issues/Bug reports/User feedback
3. Issues/Bug reports/User feedback trigger Research/Analysis
4. Research/Analysis inspire Guides/Recommendations/Templates and Proposals
5. Proposals aim to enhance Guides/Recommendations/Templates and The Protocol Specification - Back to first step.

### Issue/Bug report/User feedback
This kind of *Documentation* will mostly rely on [Usage feedback and usability](#usage-feedback-and-usability).

**Example**: Request to clarify recommended setup for synapse (Github issue).

### Research/Analysis
This kind of *Documentation* will mostly rely on [Facts backing](#facts-backing), [Sources linking](#sources-linking) and
[Peer convincing](#peer-convincing). It can be produced by anyone and will be the primary backing work for other *Documentation*.

**Example**:

- Notes on privacy and data collection of Matrix.org ([Github Gist](https://gist.github.com/maxidorius/5736fd09c9194b7a6dc03b6b8d7220d0#notes-on-privacy-and-data-collection-of-matrixorg)).
- Matrix Server ACL addition analysis ([Github gist](https://gist.github.com/maxidor/b25769f1a89c8860b928babe795bbaaf)).

### Guide/Recommendation/Template
This kind of *Documentation* will mostly rely on [Usage feedback and usability](#usage-feedback-and-usability) and
[Proposed solution](#proposed-solution).

**Example**: Matrix stack installation guide ([Github repo](https://github.com/PC-Admin/PC-Admin-s-Synapse-Setup-Guide)).

### Proposal
This kind of *Documentation* will mostly rely on [Proposed solution](#proposed-solution), [Rationalisation](#rationalisation)
and [Peer convincing](#peer-convincing).

**Example**: Matrix client auto-discovery ([Google Docs](https://docs.google.com/document/d/1vF-uWlUYmf1Xo161m871H1upJbwiIPeikWGWzaE_lrU)).

### Implementation
This kind of *Documentation* will mostly rely on [Facts backing](#facts-backing) and [Implementation](#implementation).

**Example**: any software implementation following a protocol specification.

### The Protocol Specification
The Protocol Specification will be one of the final products and the most important deliverable for the Governing Body.

As a special authoritative document, its main Proof of Work will be "delayed" and mostly contained in its ability of
[Peer convincing](#peer-convincing) and being backed by two independent [Implementation](#implementation), adding to a
total of three independent *Documentations* (one is the specification, two are the implementations). This is in line with the requirements of [BCP 9](https://datatracker.ietf.org/doc/rfc6410/?include_text=1).
