# Maple development governance

This public test repository contains a deliberately permissive, jurisdiction-neutral
[dummy policy](rules.md). It is suitable only for the explicitly configured
development deployment; it does not establish legal or policy compliance.

The policy applies only after its pull request has received the required human
approval and has been merged. CheckBox pulls and verifies the approved immutable
revision, records its identity with each decision, and fails closed when the
revision or request binding is unavailable. The Sandbox, InkBox, audit and
protected-branch boundaries continue to apply.

The agent may propose changes through a pull request, but cannot approve or
merge its own requirements changes. Keep credentials, runtime data and audit
history out of this public repository. Replace this sample with the requirements
selected for the deployment using the same protected review and update flow.
