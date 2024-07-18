# Ratify Project Contributor Ladder

Hello! We are excited that you want to learn more about the Ratify Project contributor ladder! This contributor ladder outlines the different contributor roles within the overall project, along with the responsibilities and privileges that come with them. Community members generally start at the first levels of the "ladder" and advance up it as their involvement in the project grows. Our project members are happy to help you advance up the contributor ladder.

Each of the contributor roles below is organized into lists of three types of things. "Responsibilities" are things that a contributor is expected to do, "Requirements" are qualifications a person needs to meet to be in that role, and "Privileges" are things contributors on that level are entitled to.

## Contributor

Description: A Contributor contributes directly to the project and adds value to it. Contributions need not be code. People at the Contributor level may be new contributors, or they may only contribute occasionally.

* Responsibilities include:
    * Follow the [Ratify Project CoC](CODE_OF_CONDUCT.md)
    * Follow the Ratify Project [contributing guide](CONTRIBUTING.md)
* Requirements (one or several of the below):
    * Report and sometimes resolve issues
    * Occasionally submit PRs
    * Contribute to the documentation
    * Show up at meetings, takes notes
    * Answer questions from other community members
    * Submit feedback on issues and PRs
    * Test releases and patches and submit reviews
    * Run or helps run events
    * Promote the project in public
* Privileges:
    * Invitations to contributor events
    * Eligible to become an Organization Member

## Organization Member

Description: An Organization Member is an established contributor who regularly participates in the project. Organization Members have privileges in both project repositories and elections, and as such are expected to act in the interests of the whole project.

An Organization Member must meet the responsibilities and has the requirements of a Contributor, plus:

* Responsibilities:
    * Continues to contribute regularly
    * Work to accomplish the tasks they volunteer to do within the project
* Qualifications:
    * Must have successful contributions to the project, including at least one of the following:
        * Have PRs merged and/or reviewed PRs,
        * Made contributions that resolved Issues
        * Or some equivalent combination or contribution
    * Must be actively contributing to at least one subproject, where the privileges of Organization Member will be beneficial
* Privileges:
    * May be assigned issues and reviews
    * Can trigger CI
    * Can drive project releases
    * Can be added as code owner for sub-projects
    * Can recommend other contributors to become Ratify Project Organization Members

The process for a Contributor to become an Organization Member is as follows:

1. Any organization member can open an issue in the repo [.github](https://github.com/ratify-project/.github) to nominate a new organization member.
2. Receive "LGTM" or "+1" comments from a 50% majority of Org maintainers.

## Subproject Maintainer

Subproject Maintainer is defined in [Ratify Project governance document](GOVERNANCE.md#subproject-owners).

## Org Maintainer

The Ratify Project Org maintainers are responsible for:

* Maintaining the mission, vision, values, and scope of the project
* Refining the governance and charter as needed
* Making project level decisions
* Resolving escalated project decisions when the subproject maintainers responsible are blocked
* Managing the Ratify Project brand
* Controlling access to Ratify Project assets such as source repositories, hosting, project calendars
* Deciding what subprojects are part of the Ratify Project
* Deciding on the creation of new subprojects
* Overseeing the resolution and disclosure of security issues
* Managing financial decisions related to the project

Changes to org maintainers use the following:

* Any subproject maintainer is eligible for a position as an org maintainer
* No one company or organization can employ a simple majority of the org maintainers
* An org maintainer may step down by submitting an [issue](https://github.com/ratify-project/.github/issues/new) stating their intent and they will be moved to emeritus.
* Org maintainers MUST remain active on the project. If they are unresponsive for > 3 months they will lose org maintainership unless a [two-thirds supermajority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of the other org maintainers agrees to extend the period to be greater than 3 months
* Any eligible person may stand as an org maintainer by opening a [PR](https://github.com/ratify-project/.github/pulls).
* When a PR is opened the project maintainers may vote
  * The voting period will be open for a minimum of three business days and will remain open until a [two-thirds supermajority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of project maintainers has voted
  * Only current org maintainers are eligible to vote via casting a single vote each via a -1/+1 comment on the nomination issue or approving in GitHub.
  * Once a [two-thirds supermajority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) has been reached the maintainer elect must complete [onboarding](#onboarding-a-new-maintainer) prior to becoming an official Ratify Project maintainer.
  * Once the maintainer onboarding has been completed a pull request is made on the repo adding the new maintainer to the [MAINTAINERS](MAINTAINERS) file.
* When an org maintainer steps down, they become an emeritus maintainer.

## Inactive Member

_Members are continuously active contributors in the community._

A core principle in maintaining a healthy community is encouraging active participation. It is inevitable that people's focuses will change over time and they are not expected to be actively contributing forever.

However, being a member of one of the Ratify Project organizations comes with an elevated set of permissions. These capabilities should not be used by those that are not familiar with the current state of the Ratify Project.

Therefore members with an extended period away from the project with no activity will be removed from the Ratify Project organizations and will be required to go through the org membership process again after re-familiarizing themselves with the current state. See the Ratify Project [governance document](GOVERNANCE.md#owners-structure) for the guidance on inactive subproject maintainers and org maintainers.

### How inactivity is measured

Inactive members are defined as members of the Ratify Project with **no** contributions across any repository within 12 months. Both coding and non-coding activities, such as meeting participation and event coordination, count as contributions. According to the Ratify Project [governance document](GOVERNANCE.md), inactive subproject maintainers are defined as members of the Ratify Project with **no** contributions in specific subprojects within 6 months. Inactive org maintainers are defined as members of the Ratify Project with **no** contributions in any subprojects or organization within 3 months.

**Note:** Devstats does not take into account non-code contributions. If a non-code contributing member is accidentally removed this way, they may open an issue to quickly be re-instated.

## Attributions

* This contributor ladder was created using both the [CNCF contributor ladder template](https://github.com/cncf/project-template/blob/main/CONTRIBUTOR_LADDER.md) and [Cilium contributor ladder](https://github.com/cilium/community/blob/main/CONTRIBUTOR-LADDER.md).