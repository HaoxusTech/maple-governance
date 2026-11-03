# Maple development governance

This public test repository contains a deliberately permissive, jurisdiction-neutral
[dummy policy](rules.md). It is suitable only for the explicitly configured
development deployment; it does not establish legal or policy compliance.

For this development-only bootstrap, the designated account's approval is a
delegated automated review, not an independent human review. It is recorded in
the pull request and does not establish compliance or production readiness.
After this initial bootstrap, policy changes require independent human review
before merge. CheckBox pulls and verifies the merged immutable revision, records
its identity with each decision, and fails closed when the revision or request
binding is unavailable. The Sandbox, InkBox, audit and protected-branch
boundaries continue to apply.

The agent may propose changes through a pull request, but cannot approve or
merge its own requirements changes. Keep credentials, runtime data and audit
history out of this public repository. Replace this sample with the requirements
selected for the deployment using the same protected review and update flow.
