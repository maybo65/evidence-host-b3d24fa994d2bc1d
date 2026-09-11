# Evidence host

Read-only PNG screenshots embedded as visual proof in a pull request on a private repository,
which cannot serve images to a logged-out reviewer. Contents: the same documentation file
rendered on the base branch and on the PR branch (absence -> presence), a rendered
documentation diff, a changed-files list, and a CI checks panel. No source code, credentials,
or customer data.

URLs are pinned to an immutable commit sha, so an embedded image can never be silently
swapped for different bytes.
