# ContainerSSH Charter

ContainerSSH is a **free, open source project, and must remain so**. Our main mission is to improve upon ContainerSSH with the goal to create containers for SSH users without having to set up system users.

This charter covers **important processes and decisions that impact the whole organization, direction, and goals**. Small decisions like coding style per repository or similar details can be decided among the repository maintainers.

## Working Group

The working group *(WG)* consists of:
* 3 chairs with equal rights who
  - Enforce the [Code of Conduct](CODE_OF_CONDUCT.md)
  - Have administrative rights over the GitHub org, communication channels, and other community-owned resources
  - Publicly record decisions made by the WG in the [wg-decisions](wg-decisions) folder
* Individuals who want to join the WG and pass a review of their PR sent to [WG_MEMBERS.md](WG_MEMBERS.md)), with approval depending on any one or more of the below requirements:
  - They contribute with code, documentation, artwork, articles, videos, talks, or similar additions to the ContainerSSH ecosystem
  - They are an active user of ContainerSSH (end user, product builder, researcher, etc. - please describe your use case in the PR, you do not have to mention any company names or details)
  - They are actively helping community members on any of the official ContainerSSH channels

### Termination of WG membership

A Working Group member *(including chairs)* that does not participate in working group matters *without reason and notice* (voting and/or meetings) for 3 times in a row leaves the working group automatically as we can assume they are not interested in being a member of the WG anymore. This ensures that we do not have a corpus of inactive members with voting rights.

Additionally, as stated in the [Code of Conduct](CODE_OF_CONDUCT.md), chairs can remove a WG member if their behavior is clearly disruptive to the community.

## Decision Proposals

Decisions can be started *only asychronously* in the [community repository pull requests](https://github.com/ContainerSSH/community/pulls) via submitting a pull request with a new file to [wg-decisions/proposals](wg-decisions/proposals). You can use the included `template.md` file as a guideline.

## Voting

Each member of the working group is eligible for voting if they have been a member of the WG for at least 30 days. For any decision that impacts the whole project or processes, a vote is started where a 66% majority with a quorum of 66% of all WG members is needed for the proposal to pass.

If the majority cannot be reached, the proposal is considered rejected and can be brought to the WG again 2 months after the rejection at the earliest. If the same decision has been rejected twice, it cannot be brought to the WG again.

Any voting period must last at least 7 days to account for different time zones and other obligations. Silence means abstaining from a vote.

WG members cast their votes by approving or rejecting the decision suggested via a pull request. Once the voting period is over, the chairs record the decision, objections, and other relevant information in the `wg-decisions` folder.

## Chair Elections

If a chair leaves through non-participation or through their own announcement, elections for a new chair take place.

After the announcement of a chair leaving, there is a period of 30 days for nominations (from the date of the announcement). Any WG member can nominate another WG member or themselves, while a second member has to sponsor the nomination. Only members that have been part of the WG for 6+ months are eligible to become a chair or sponsor a nomination.

After the nomination period, elections take place asynchronously through the same process as standard decision proposals.

## Changing the Charter

This charter can only be changed by suggestions first passing through a 66% majority of WG members and a subsequent 66% vote among the chairs.