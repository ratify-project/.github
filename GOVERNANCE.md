# Ratify Governance

The following document outlines Ratify project governance.

## The Ratify Project

The Ratify project consists of several repositories known as sub-projects that enable community cohorts to experiment and implement solutions across the scope of the project.

## Owners Structure

There are two types of owners in the Ratify project organized hierarchically. Ratify [org owners][ratify-project-owners] oversee the overall project and its health. Subproject owners focus on a single repository, a group of related repositories, a service (e.g., a website), or subproject to support the other subprojects (e.g., marketing or community management). 

Changes in Ratify Org owners have to be announced via an [ratify-project/community/issues][ratify-issues-new]. Changes to sub-project owners are to be announced via the appropriate sub-project issue.

### Owner Responsibility

Ratify owners adhere to the requirements and responsibilities set forth in the respective [Ratify Org Owners](#ratify-org-owners) and [Subproject Owners](#subproject-owners). They further pledge the following:

- To act in the best interest of the project and subprojects
- To ensure that project and subproject development and direction is a function of community needs
- To take action when reasonably confident that it is the right action to take
- To fulfill the responsibilities outlined in this document and its dependents

### Ratify Org Owners

The [Ratify Org owners][ratify-project-owners] are responsible for:

- Maintaining the mission, vision, values, and scope of the project
- Refining the governance and charter as needed
- Making project level decisions
- Resolving escalated project decisions when the subproject owners responsible are blocked
- Managing the Ratify brand
- Controlling access to Ratify assets such as source repositories, hosting, project calendars
- Deciding what subprojects are part of the Ratify project
- Deciding on the creation of new subprojects
- Overseeing the resolution and disclosure of security issues
- Managing financial decisions related to the project

Changes to org owners use the following:

- Any subproject owner is eligible for a position as an org owner
- No one company or organization can employ a simple majority of the org owners
- An org owner may step down by submitting an [issue][ratify-issues-new] stating their intent and they will be moved to emeritus.
- Org owners MUST remain active on the project. If they are unresponsive for > 6 months they will lose org ownership unless a [two-thirds supermajority][super-majority] of the other org owners agree to extend the period to be greater than 6 months
- When there is an opening for a new org owner, any current owners may nominate a suitable subproject owner as a replacement
  - Nominations for new owners must be made by creating an [issue][ratify-issues-new].
- When nominated individual(s) agrees to be a candidate for ownership, the subproject owners may vote
  - The voting period will be open for a minimum of three business days and will remain open until a [two-thirds supermajority][super-majority] of project owners has voted
  - Only current org owners are eligible to vote via casting a single vote each via a +1 comment on the nomination issue
  - Once a [two-thirds supermajority][super-majority] has been reached the owner elect must complete [onboarding](#onboarding-a-new-owner) prior to becoming an official Ratify owner.
  - Once the owner onboarding has been completed a pull request is made on the repo adding the new owner to the [OWNERS][ratify-project-owners] file.
- When an org owner steps down, they become an emeritus owner

Once an org owner is elected, they remain an owner until stepping down (or, in rare cases, are removed). Voting for new owners occurs when necessary to fill vacancies. Any existing subproject owner is eligible to become an org owner.

The Org Owners will select a chair to set agendas and call meetings of the Org Owners. Chairs will serve a term of 6 months, once the term is complete org owners will select a subsequent chair.

### Subproject Owners

Subproject owners are responsible for activities surrounding the development and release of content (eg. code, specifications, documentation) or the tasks needed to execute their subproject (e.g., community management) within the designated repository, or repositories associated with the subproject (e.g., community management). Technical decisions for code resides with the subproject owners unless there is a decision related to cross owners groups that cannot be resolved by those groups. Those cases can be escalated to the org owners.

Subproject owners many be responsible for one or many repositories.

Subproject owners do not need to be software developers. No explicit role is placed upon them and they can be anyone appropriate for the work being produced. For example, if a repository is for documentation it would be appropriate for owners to be technical writers.

Changes to owners use the following:

- A subproject owner may step down by submitting an [issue][ratify-issues-new] stating their intent and they will be moved to emeritus.
- Owners MUST remain active. If they are unresponsive for > 6 months they will be automatically removed unless a [two-thirds supermajority][super-majority] of the other subproject owners agrees to extend the period to be greater than 6 months
- New owners can be added to a subproject by a [two-thirds supermajority][super-majority] vote of the existing owners
- When a subproject has no owners the Ratify org owners become responsible for it and may archive the subproject or find new owners

### Onboarding a New Owner

New Ratify owners participate in an onboarding period during which they fulfill all code review and issue management responsibilities that are required for their role. The length of this onboarding period is variable, and is considered complete once both the existing owners and the candidate owners are comfortable with the candidate's competency in the responsibilities of ownership. This process MUST be completed prior to the candidate being named an official Ratify owner.

The onboarding period is intended to ensure that the to-be-appointed owner is able/willing to take on the time requirements, familiar with Ratify core logic and concepts, understands the overall system architecture and interactions that comprise it, and is able to work well with both the existing owners and the community.

## Decision Making at the Ratify org level

When owners need to make decisions there are two ways decisions are made, unless described elsewhere.

The default decision making process is [lazy-consensus][lazy-consensus]. This means that any decision is considered supported by the team making it as long as no one objects. Silence on any consensus decision is implicit agreement and equivalent to explicit agreement. Explicit agreement may be stated at will.

When a consensus cannot be found a owner can call for a [majority][majority] vote on a decision.

Many of the day-to-day project maintenance can be done by a lazy consensus model. But the following items must be called to vote:

- Removing an owner for any reason other than inactivity (super majority)
- Changing the governance rules (this document) (super majority)
- Licensing and intellectual property changes (including new logos, wordmarks) (simple majority)
- Adding, archiving, or removing subprojects (simple majority)

Other decisions may, but do not need to be, called out and put up for decision via creating an [issue][ratify-issues-new] at any time and by anyone. By default, any decisions called to a vote will be for a _simple majority_ vote.

## Code of Conduct

This Ratify project has adopted the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md).

## Attributions

This governance model we created using both the [SPIFFE](https://github.com/spiffe/spire/blob/main/MAINTAINERS.md) and [Helm](https://github.com/helm/community/blob/main/governance/governance.md) governance documents.

## DCO and Licenses

The following licenses and contributor agreements will be used for Ratify projects:

- [Apache 2.0](https://opensource.org/licenses/Apache-2.0) for code
- [Developer Certificate of Origin](https://developercertificate.org/) for new contributions

[ratify-project-owners]:  OWNERS.md
[lazy-consensus]:         http://communitymgt.wikia.com/wiki/Lazy_consensus
[majority]:               https://en.wikipedia.org/wiki/Majority
[ratify-issues-new]:      https://github.com/ratify-project/.github/issues/new
[super-majority]:         https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote