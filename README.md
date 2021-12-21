# RFC process

A team SHOULD publish one or several RFCs for any feature, service or project they want to develop, RFCs are the first step in the delivery of any meaningful change to our tech ecosystem. All groups should follow this police and register their proposals in a document and request for comments amongst their peers.

 In that regards they need to write down a design document on such change, it’s important to state, the problem they aim to solve and how they will do so, plus add possible drawbacks of the picked solution, if the group has also done analysis on alternative solutions, it is highly recommended to also add those, plus the reason why they were discarded.

Once the document is done, this document should be presented to their leadership group: convoy director and engineering managers (EM), if the convoy has senior enough engineers (engineers in the tech track), the convoy leaders should appoint them to also review their RFCs.

The group, shall read the document and provide initial feedback, if the group considers that this document goes beyond their area of expertise or domain, they should request comments from others who could help them, either by directly contacting another convoy, if the domain overlaps, or the Stuart Tech leadership, in which case, both should resolve promptly with an adequate group of experts to review and comment the proposed RFC in a timely manner.

## Status

Each RFC should have an status, the status should be reflected on the title and it is the group proposing it, responsible of keeping it up to date.

*WIP*: the team is writing the document, analysing alternatives and so on. No limit of time it can be in this status.

*PROPOSAL*: The convoy leadership is analysing it. They can suggest changes, which if very deep can make it back to WIP. If they discard it right away it goes to the DISCARDED status. If they decide that falls outside the convoy boundaries, they move it to DRAFT so the tech governance can check it. If they think that can be adopted right away, they move it to the status of ACCEPTED. The RFC can be only a limited amount of time in this status (2 weeks?), or less if there is an explicit answer from the leadership.

*DRAFT*: The tech gov is analysing it. They can suggest changes which if deep will move it to WIP. They can move it to DISCARDED, or to ACCEPTED. The RFC can be only a limited amount of time in this status (2 weeks?), or less if there is an explicit answer from the gov committee.

*ACCEPTED*: The RFC is published in all the required channels. It will stay there a limited amount of time in this status (2 weeks?), so all people in the company can raise their concerns, or start adopting it. If the convoy leadership or the gov committee think that the concerns raised are important, they can move it to DRAFT again. Otherwise it gets moved to STANDARD.

*STANDARD*: The RFC is adopted as a guideline for all teams for which it is relevant. The convoy leadership and the tech gov will pay attention to old and new developments to be aligned with it. It can only become DEPRECATED.

*DISCARDED*: The RFC is discarded and will not be adopted. It is kept for the record.

## Workflow

Write a technical document with the proposal.

You should use [our template to start the RFC](docs/template.md)

- Be precise and clear.
- State what are you trying to solve and why.
- Mention drawbacks (if any) of the proposed solution.
- Mention alternative options and why you have discarded.

Request for comments within your convoy leadership.

- Convoy leadership + Lead (and Staff if any) engineers within the convoy should decide if they approve the RFC or go to the tech governance.
- The convoy leadership could also request for comments from outside their group if the proposal goes beyond their domain or expertise.
- (Optional) Request for comments to the tech governance group.

The convoy leadership owning the RFC should add a topic to the weekly meeting so a person or group should be appointed to review the RFC in a timely manner.

The leadership owning the RFC (EM or Director) should be looking for approvals from the reviewers and make sure the proposal gets green lighted.

Once approved the RFC should be communicated to the company and made public for consulting.

## Execution and Communication

Once the RFC is approved, it itself should include a plan to execute it if deemed necessary, for instance an RFC about an engineering policy should specify when and how this policy will be executed.

Also communication is an important aspect of the RFCs, for that we should establish a global channel where the RFCs are announced once approved (monthly email to tech) and a curated and searchable repository of RFCs (Github repo). It is the responsibility of the tech governance team to keep this communication flowing.
