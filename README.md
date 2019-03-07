# Technical Steering Committee

A Technical Steering Committee(TSC) for multiple projects serves as a replacement for the current BDFL that oversees a few of the projects that exist today.
These changes should have a minimal impact to the day-to-day operations and governance model in order to make a transition smooth and timely.

This proposal provides enough initial structure to elect the committee and hand off responsibilities to this group of diverse individuals.

**Edits to this charter requires that the projects the TSC oversees vote with a simple majority on all changes.**

Small edits to this charter such as typos and formatting can be approved by the TSC members.

## Committee Information

The Technical Steering Committee acts as an escalation point for conflicts within projects, encourage cross-project communication/coordination and help with project governance.
The TSC is not involved in the day-to-day development or maintenance of the projects it represents, though, individuals on the committee may be maintainers and/or contributors to the projects.
The committee does not make day-to-day technical decisions on architecture, code acceptance, or feature set but can resolve technical disputes in these areas when an issue has been escalated to the TSC by the community of the project.
However, escalation should be considered a failure of the community process when unable to reach concensus on an issue.

### Responsibilities

The committee should:

1. Serve as an escalation point for members of the community to file a dispute or report concerns on technical issues.
2. Ensure that appropriate communication exists between projects.
3. Keep a public record of escalations, actions, and decisions.

*If non-technical issues are escalated to the TSC, the TSC should route the issue to the appropriate destination for the affected project.  i.e. Code of Conduct issues to CNCF or Docker CoC boards.*

### Seat Term

**2 years**

Members do not have a set term limit, the seat they hold has a term limit.
Members are rotated organically as seats expire and members are either re-elected or replaced.

Every two years the seats expire and a new election process begins.
Members are able to re-run for election as long as they qualify for the **Candidate Requirements**.

### Committee Size

**7 seats**

A single company cannot hold more than 1/3 (one-third) of the seats on the committee.

### Elections

Members of the TSC will be voted in by the maintainers of the projects that it represents.
Each project receives one vote in the election.
The departing BDFL, Solomon Hykes, will receive one vote in every election.

The top 7 candidates will comprise the TSC.
Elections will be handled via http://civs.cs.cornell.edu/ using ranked voting.
Each project will receive one vote that the maintainers of the project must decide on.
This ensures projects with a large number of maintainers will not be able to influence the voting more than smaller projects.
It is up to the projects to determine how they want to rank their votes in an election.
A suggested method for projects is to use the same ranked voting with their maintainers to cast their vote.

*Why ranked voting?: “Ranked-choice voting gives more accurate results because it collects more information from voters. It also helps avoid vote splitting and spoilers.”*

#### Candidate Requirements

1. Anyone is eligible.
2. Must be sponsored by a maintainer of a TSC represented project.
3. Maintainers cannot sponsor themselves.

## TSC Mailing List

tsc@mobyproject.org

## TSC Represented Projects

* [InfraKit](https://github.com/docker/infrakit)
* [LinuxKit](https://github.com/linuxkit/linuxkit)
* [Moby](https://github.com/moby/moby)
* [SwarmKit](https://github.com/docker/swarmkit)
* [libnetwork](https://github.com/docker/libnetwork)
* [notary](https://github.com/docker/notary)
