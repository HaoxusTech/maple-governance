# Synthetic governance test: maple-account-smoke-20261121-b84f

## Test-only scope

This proposed requirement applies only to fictional release-readiness records
explicitly identified as part of test `maple-account-smoke-20261121-b84f`.
It does not apply to production records or unrelated tests.

## Named owner

Each in-scope fictional release-readiness record must include an explicitly
named fictional owner. An empty owner field or an unspecified placeholder does
not satisfy this requirement. For example, `Synthetic Release Team` is a named
fictional owner. A named owner does not establish acceptance or release approval.

When reviewing a request to create or update an in-scope record, inspect the
resulting record and reject the request if the fictional owner is missing or
cannot be verified from the available evidence. Explain the missing information.
Within this test-only scope, this requirement takes precedence over a general
development allow-all rule; unrelated requirements remain unchanged.

## Proposal status

This text uses only fictional information. It is a proposal for human review,
not an active requirement. Opening the PR does not activate policy or modify
existing records. Human review and merge, followed by deployment selection of
the immutable approved revision, are required before it becomes applicable.
