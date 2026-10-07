# Prelint integration check

This document provides a small, documentation-only pull request for checking
Prelint's GitHub integration. It does not change game behavior.

## Verify a review

1. Open a ready-for-review pull request in `pthebesfsu-a11y/Band-Kungfu`.
2. Look for a Prelint check or review on the pull request and a corresponding run
   in the Band-Kungfu project's Prelint Reviews page.
3. Confirm that the run finishes for the pull request's latest commit. A completed
   review with no findings is a successful integration check.

If no run appears, check that repository review monitoring is enabled and the
review trigger is Automatic. For an on-request review, use the Run review button
in Prelint or comment `@prelint` on the pull request.

This checks review delivery only. It does not verify the quality of findings or
replace the project's game and server checks.
