---
title: RFC Process
---

Below is an overview of the RFC process[^mep], it is designed to be simple and structured as well as help document the evolving decisions and scope for OXA.

[^mep]: This process is based on MyST Enhancement Proposals (<https://mep.mystmd.org>) and others in the Jupyter and Python ecosystem.

## Step 1: Open an Issue

Open an issue in [oxa-dev/rfc](https://github.com/oxa-dev/rfc) and discuss in Discord. The issue should roughly describe the proposal and help others understand your idea and get informal alignment around it. It will also serve as an early signal if the proposal is not well-suited for the RFC process, saving you from investing too much time!

## Step 2: Open a Pull Request

Use a Markdown template below to structure your proposal. Here's a proposed template:

```yaml
---
title: Title of the RFC
---

## Context

<!-- provide context needed to understand this proposal. Describe the problem or opportunity that this RFC addresses. -->

## Proposal

<!-- describe your proposed change in concrete terms. Include a layperson's description of this change if relevant. -->

## Examples

<!-- provide examples of what this change would look like in the real world (e.g., code examples, API designs, architecture diagrams). -->

<!-- reference other examples you're using for inspiration or to help others learn and understand the proposal. -->

## Implementation implications

<!-- describe how this would improve the system or functionality. Describe any deprecations or migration steps that would be needed. -->

## Questions or Objections

<!-- as conversation takes place, list common questions/objections with responses. -->
```

Update the `myst.yml` in the folder to include the RFC authors, date. Repeat authors can be added to the `rfc.yml`. Look to the initial RFC for a guide. The Steering Council should do a quick review, and add a `draft` label to the Pull Request. A comment will appear with the draft of the rendered content.

## Step 3: Discuss and Iterate

Invite discussion from others in the community, incorporate new ideas and improve the clarity of the RFC. Discussion can take place in the GitHub Pull Request, in the [Discord](https://discord.oxa.dev) `#rfc` channel, or in other appropriate forums.

## Step 4: Activate Decision Making

Once the proposal has stabilized and the author wishes to move forward, do the following:

- The [Steering Council](#steering-council-members) changes to an `active` label to the Pull Request.
- The [Steering Council](#steering-council-members) should review the RFC and approve if they wish to accept it.
  - To approve, click `Approve` the GitHub Pull Request UI.
  - To request blocking changes, then click `Request Changes` in the GitHub UI.
- An RFC may be accepted when the following conditions are met:
  - More than five (5) weekdays have passed since the proposal was marked as `active`.
  - At least two `PR Approvals` from [Steering Council](#steering-council-members).
  - No `Request Changes` from a Steering Council member.
- If there are **unresolved objections** (via `Request Changes` in GitHub)
  - The RFC author may restart the decision making process after incorporating feedback to resolve the objection.
  - The RFC author or the Steering Council may also set the label to `rejected`, and merge to maintain a record for the community.
- When accepted, merge the Pull Request and close the issue. 🎉

## Step 5: Implement the RFC

When an RFC has been accepted, work can begin on implementation.
Implementation should follow the project's standard [development practices](./practices.md).
