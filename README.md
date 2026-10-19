# pytxo-scans

Runs [`pytxo land`](https://pytxo.com/docs/getting-started/land-in-ci) on a public
repository's open pull requests, combined, to see whether they still pass their
checks together. Scans are started by hand (`workflow_dispatch`), run on
GitHub-hosted runners with no secrets and no token permissions, and never push,
comment or merge anywhere.

Results are in each run's job summary.
