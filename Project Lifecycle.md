# Node.js Foundation Project Lifecycle

## Project Definition

The Node.js Foundation hosts several "Top Level Projects." These projects are autonomous from each other and governed by their own TC (Technical Committee) and chartered by the Node.js Foundation TSC.

Projects are free to create "Working Groups" which are autonomous groups collaborating to fulfill a set of responsibilities. Working Groups are eventually chartered by the TC. The TSC also charters its own Working Groups.

```
 TSC
  |
  |-- Project A TC (Chartered By TSC)
  |       |-- Working Group (Chartered By Project TC)
  |
  |-- Project B TC (Chartered By TSC)
  |       |-- Working Group (Chartered By Project TC)
  |
  |-- Working Group A (Chartered by TSC)
  |-- Working Group B (Chartered by TSC)
```

Both TLDs and TSC WGs may elect a representative to the TSC. TLDs and WGs with *incubation* status are not granted voting privileges on the TSC.

## Incubation

The purpose of incubation is to support and mentor projects entering the foundation. The goal is for projects to be:

* Participatory
* Transparent
* Effective

While certain processes are strongly recommended because of the TSC's experience the goal of incubation is not to enforce a specific set of processes but to ensure that the processes adopted and accepted by a project achieve these goals. Therefor, the requirements for graduating from incubation are based on metrics that demonstrate success in terms of these values. These metrics are:

* TC is 5 members or greater.
* No more than 1/4 of the TC is affiliated with the same employer.
* Members of the TC live in at least 4 different timezones.
* The decision making process is documented and publicly accessible.

A project may apply to graduate from incubation at any time by calling for a vote in the TSC.

## Lifecycle

The Foundation shall encourage new Projects and innovation in the community. New Projects enter the Node.js Foundation through a [Proposal](#Proposal).

Project should have some prior history, be considered mature and contain a wide contributorship before submitting a proposal to enter the foundation.

## Top Level Project and Working Group Requirements

All TLPs and WGs are expected to operation in a transparent manor. Decisions must be made publicly through a documented public process managed by each TLP TC or WG.

All TLPs and WGs must use a participatory decision making process. All TLP TCs must ensure they are accurately representing the WGs in their TLP.

## Top Level Projects

All Top Level Project TCs must follow a [Consensus Seeking](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making) process and are responsible for documenting and keeping up to date their current processes and practices.

Each TLP TC must elect a representative to the Node.js Foundation TSC or vote to abstain from representation on the TSC.

## Applying to join

A proposal to join the Node.js Foundation as a Top Level Project or Working Group must include:

* Introduction and project description.
* Project history.
* Any available metrics or even estimates about the user base, ecosystem and community.
* Project scope.
* Project governance process.
* Project contribution process.
 * Must include [DCO](https://github.com/nodejs/io.js/blob/master/CONTRIBUTING.md#developers-certificate-of-origin-10).
 * Must include approved license (MIT, Apache2, etc).
 * Must include a [Code of Conduct](https://github.com/nodejs/io.js/blob/master/CONTRIBUTING.md#code-of-conduct).
* List of current tools in use by the project (forums, issue trackers, GitHub orgs, etc).
* Existing IP Policy and relevant intellectual property (trademarks, domain names, etc).
* List of initial TC members.
* List of initial Working Groups.

Each proposal should be sent as a pull request to this repository in the Applications directory. Proposals do not have to be complete to be submitted, the TSC can work with the authors and their respective communities in each Pull Request.