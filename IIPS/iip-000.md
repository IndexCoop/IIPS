---
iip: 0
title: IIP Purpose and Guidelines
status: Proposed
author: Index Community
discussions-to: https://gov.indexcoop.com/
created: 2020-10-8
---

## Context

Welcome to the Index Cooperative community! We are thrilled with how fast you guys have started developing a shared vision and begun participating in debates, discussions, and proposals. So far, this is one of the healthiest community launches we have ever seen in the crypto space.

When thinking about governance in the context of Index Cooperative, we see these as the major governance functions:

| Action                | Example |
|---                    |---|
| Fee split             | Editing the fee split between sponsors and the coop  |
| Treasury              |  Deploying treasury funds |
| Index Asset Upgrade   | Migrating LEND to AAVE (but not changing the fundamental index composition)  |
| Procedural Changes    | IIP-0 Discussing Proposals  |
| Index Additions       | Approving other indexes proposed by sponsors  |
| Rebalance Execution*  | Executing a rebalance for DPI  |


Of course, this is only an initial setting. There are so many other ways the community can monetize or interact with the indexes like loaning out constituent assets and participating in component protocol governance that the community can add over time.

We expect IIP-0 to govern most of the actions above outside of Index Additions and Rebalance Executions. Those actions are much more complex and a totally new area of governance that no one has really ever explored. We will be releasing an outline of a follow up for how we expect Index Additions to be governed for the community to review. 

Rebalance execution has an asterisk as decentralizing that process is currently in R&D by the team. We will be updating everyone as we get more clarity on how the smart contracts will work.

Please respond to this thread or post in the community forum if you would like to be an editor!

## What is an IIP?
IIP stands for Index Improvement Proposal, it has been adapted from the SIP (Synthetix Improvement Proposal) and YIP (Yearn Improvement Proposal). The purpose of this process is to ensure changes to Index Cooperative are transparent and precise. An IIP is a design document providing information to the Index Cooperative community about a proposed change to the system. The author is responsible for building consensus within the community and documenting dissenting opinions.

## IIP Rationale
We intend IIPs to be the primary mechanisms for proposing new features, collecting community input on an issue, and for documenting the design decisions for changes to Index Cooperative. Because they are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.
It is highly recommended that a single IIP contain a single key proposal or new idea. The more focused the IIP, the more successful it is likely to be.
An IIP must meet certain minimum criteria. It must be a clear and complete description of the proposed enhancement. The enhancement must represent a net improvement.

## IIP WorkFlow
Parties involved in the process are the author, the IIP editors, and the Index Cooperative community.
Before you begin, vet your idea, this will save you time. Ask the Index Cooperative community first if an idea is original to avoid wasting time on something that will be rejected based on prior research (searching the Internet does not always do the trick). It also helps to make sure the idea is applicable to the entire community and not just the author. Just because an idea sounds good to the author does not mean it will have the intended effect. The appropriate public forum to gauge interest around your IIP is the Index Cooperative Discord or the Index Cooperative governance forum.
Your role as the champion is to write the IIP using the style and format described below, shepherd the discussions in the appropriate forums, and build community consensus around the idea. The following is the process for an IIP:

```
Proposed -> Approved -> Implemented
  ^                     |
  +----> Rejected       +----> Moribund
  |
  +----> Withdrawn
  v
Deferred
```

Each status change is requested by the IIP author and reviewed by the IIP editors. Use a pull request to update the status. Please include a link to where people should continue discussing your IIP. The IIP editors will process these requests as per the conditions below.

* **Work in progress (WIP)** -- Once the champion has asked the Index Cooperative community whether an idea has any chance of support, they will write a draft IIP as a pull request. Consider including an implementation if this will aid people in studying the IIP.
* **Proposed** -- If agreeable, IIP editor will assign the IIP a number (generally the issue or PR number related to the IIP) and merge your pull request. The IIP editor will not unreasonably deny an IIP. Proposed IIPs will be discussed on governance calls, governance forum, and in Discord. If there is a reasonable level of consensus around the change on the governance forum poll the change will be moved to approved. If the change is contentious, a vote of token holders may be held to resolve the issue or approval may be delayed until consensus is reached.
* **Approved** -- This IIP has passed community governance and is now being prioritised for development.
* **Implemented** -- This IIP has been implemented and deployed to mainnet.
* **Rejected** -- This IIP has failed to reach community consensus.
* **Withdrawn** -- This IIP has has been withdrawn by the author(s).
* **Deferred** -- This IIP is pending another IIP/some other change that should be bundled with it together.
* **Moribund** -- This IIP has been implemented and is now obsolete and requires no explicit replacement.

## What belongs in a successful IIP?
Each IIP should have the following parts:
* **Preamble** - RFC 822 style headers containing metadata about the IIP, including the IIP number, a short descriptive title (limited to a maximum of 44 characters), and the author details.
* **Simple Summary** - “If you can’t explain it simply, you don’t understand it well enough.” Provide a simplified and layman-accessible explanation of the IIP.
* **Abstract** - a short (~200 word) description of the technical issue being addressed.
* **Motivation*** - The motivation is critical for IIPs that want to change Index Cooperative. It should clearly explain why the existing specification is inadequate to address the problem that the IIP solves. IIP submissions without sufficient motivation may be rejected outright.
* **Specification*** - The technical specification should describe the syntax and semantics of any new feature.
* **Rationale** - The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.
* **Test Cases*** - Test cases may be added during the implementation phase but are required before implementation.
* **Copyright Waiver** - All IIPs must be in the public domain. See the bottom of this IIP for an example copyright waiver.
*If you feel like certain sections are not relevant to the proposal, please include that acknowledgement in the submission to the IIP editor.

## IIP Formats and Templates
IIPs should be written in markdown format. Image files should be included in a subdirectory of the assets folder for that IIP as follows: assets/IIP-X (for IIP X). When linking to an image in the IIP, use relative links such as ../assets/IIP-X/image.png.

` IIP Header Preamble` Each IIP must begin with an RFC 822 style header preamble, preceded and followed by three hyphens (---). This header is also termed "front matter" by Jekyll. The headers must appear in the following order. Headers marked with "*" are optional and are described below. All other headers are required.

` IIP`: (this is determined by the IIP editor)

` title`: The IIP title

` author`: A list of the author's or authors' name(s) and/or username(s), or name(s) and email(s). Details are below.

` discussions-to`: a url pointing to the official discussion thread at gov.indexcoop.com

` status`:  WIP | PROPOSED | APPROVED | IMPLEMENTED 

` created`: A date in ISO 8601 format (yyyy-mm-dd)

` updated`: A date in ISO 8601 format (yyyy-mm-dd)

` requires`: IIP number(s)

` resolution`: A url pointing to the resolution of this IIP

Headers that permit lists must separate elements with commas.
Headers requiring dates will always do so in the format of ISO 8601 (yyyy-mm-dd).

#### `author` header

The `author` header optionally lists the names, email addresses or usernames of the authors/owners of the IIP. Those who prefer anonymity may use a username only, or a first name and a username. The format of the author header value must be:

> Random J. User &lt;address@dom.ain&gt;

or

> Random J. User (@username)

if the email address or GitHub username is included, and

> Random J. User

if the email address is not given.

#### `discussions-to` header

While an IIP is in WIP or Proposed status, a `discussions-to` header will indicate the URL at [gov.indexcoop.com](https://gov.indexcoop.com/) where the IIP is being discussed.

#### `created` header

The `created` header records the date that the IIP was assigned a number. Both headers should be in yyyy-mm-dd format, e.g. 2001-08-14.

#### `updated` header

The `updated` header records the date(s) when the IIP was updated with "substantial" changes. This header is only valid for IIPs of Draft and Active status.

#### `requires` header

IIPs may have a `requires` header, indicating the IIP numbers that this IIP depends on.

## Auxiliary Files
IIPs may include auxiliary files such as diagrams. Such files must be named IIP-XXXX-Y.ext, where “XXXX” is the IIP number, “Y” is a serial number (starting at 1), and “ext” is replaced by the actual file extension (e.g. “png”).

## IIP Editors
The current IIP editors are:
* Abhishek Punia (@puniaviision)
* Dylan Tran (@controtie)
* Inje Yeo (@inje)

## IIP Editor Responsibilities
For each new IIP that comes in, an editor does the following:

- Read the IIP to check if it is ready: sound and complete. The ideas must make technical sense, even if they don't seem likely to get to final status.
- The title should accurately describe the content.
- Check the IIP for language (spelling, grammar, sentence structure, etc.), markup (Github flavored Markdown), code style

If the IIP isn't ready, the editor will send it back to the author for revision, with specific instructions.

Once the IIP is ready for the repository, the IIP editor will:

- Assign an IIP number (generally the PR number or, if preferred by the author, the Issue # if there was discussion in the Issues section of this repository about this IIP)
- Merge the corresponding pull request
- Send a message back to the IIP author with the next step.

The IIP editors monitor IIP changes, and correct any structure, grammar, spelling, or markup mistakes we see.
The editors don't pass judgment on IIPs. They merely do the administrative & editorial part.

## History
The IIP document was derived heavily from the SIP Synthetix Improvement Proposal and the YIP Yearn Improvement Proposal. The document in many places was simply copied and modified. Any comments about the IIP document should be directed to the IIP editors.

## Copyright
Copyright and related rights waived via CC0.

