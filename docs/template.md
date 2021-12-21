# RFC Template

Status (WIP / Proposal / Draft / Accepted / Standard / Discarded)

## RFC

NNN (update when you have a link to the PR #)

### Author(s)
My Name (me@stuart.com), AN Other (you@stuart.com)

### Sponsor
A N Expert (whomever@stuart.com)

### Obsoletes
ST-RFC it replaces, else remove this header

### Objective
What are we doing and why? What problem will this solve? What are the goals and non-goals? This is your executive summary; keep it short, elaborate below.

### Motivation

Why this is a valuable problem to solve? What background information is needed to show how this design addresses the problem? Which users are affected by the problem? Why is it a problem? What data supports this? What related work exists?
User Benefit

How will users (or other contributors) benefit from this work? What would be the headline in the release notes or blog post?
Design Proposal

This is the meat of the document, where you explain your proposal. If you have multiple alternatives, be sure to use sub-sections for better separation of the idea, and list pros/cons to each approach. If there are alternatives that you have eliminated, you should also list those here, and explain why you believe your chosen approach is superior.

Make sure you’ve thought through and addressed the following sections. If a section is not relevant to your specific proposal, please explain why, e.g. your RFC addresses a convention or process, not an API.
Alternatives Considered

Make sure to discuss the relative merits of alternatives to your proposal.

### Performance Implications

Do you expect any (speed / memory)? How will you confirm?

There should be microbenchmarks. Are there?

There should be end-to-end tests and benchmarks. If there are not (since this is still a design), how will you track that these will be created?

### Dependencies

Does this proposal add any new dependencies to Stuart architecture?

Dependent projects/services: are there other areas of Stuart services or things that we use at Stuart tech (CI, Kafka, infra, etc.) that this affects? How have you identified these dependencies and are you sure they are complete? If there are dependencies, how are you managing those changes?

### Engineering Impact

Do you expect changes to binary size / startup time / build time / test times?

Who will maintain this code? Is this code in its own buildable unit? Can this code be tested in its own? Is visibility suitably restricted to only a small API surface for others to use?

### Platforms and Environments

Execution environments (Cloud services, accelerator hardware): what impact do you expect and how will you confirm?

Platforms: does this work on all platforms supported by Stuart? If not, why is that ok? Will it work on embedded/mobile? For instance: does it impact automatic code generation or mobile stripping tooling?

### Best Practices

Does this proposal change best practices for some aspect of using/developing at Stuart? How will these changes be communicated/enforced?

### Compatibility

Does the design conform to the backwards & forwards compatibility requirements?

How will this proposal interact with other parts of the Stuart Ecosystem?

### User Impact

What are the user-facing changes? How will this feature be rolled out?

### Detailed Design

Elaborate on details if they’re important to understanding the design, but would make it hard to read the proposal section above.

### Questions and Discussion Topics

Seed this with open questions you require feedback on from the RFC process.

