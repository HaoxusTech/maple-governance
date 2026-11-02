# Maple deployment governor rules

This repository holds the human-approved governance rules for one Maple
deployment. It is separate from that deployment's workspace repository. The
agent may propose rule changes through a pull request; a human must approve
before merge. Protected branch and identity settings must prevent the agent
from directly writing, self-merging or activating rules.

[rules.md](rules.md) is a starting point, not an approved or complete policy.
An authorized human must define and approve the actual rules. Trusted CheckBox
code must load only an approved merged revision, bind decisions to it and fail
closed when the required approved rules are unavailable. Do not put credentials,
audit history or runtime data in this repository.

Creating this repository or copying these files does not configure branch
protection, establish human approval, or activate a policy.
