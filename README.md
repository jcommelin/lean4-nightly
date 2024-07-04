# lean4-nightly

This repository hosts automatically generated Lean [toolchains](https://github.com/leanprover/elan#elan-lean-version-manager) for Lean nightly builds.

You should not need to use this repository directly. Instead:
* Once your Lean pull request has the [`toolchain-available`](https://github.com/leanprover/lean4/pulls?q=is%3Apr+is%3Aopen+label%3Atoolchain-available) label,
* Edit the `lean-toolchain` file in the project you would like to test your pull request in to say:
  `leanprover/lean4:nightly-YYYY-MM-DD`, where `YYYY-MM-DD` is the date of the nighly you want to use (e.g. `2023-11-01`).

* See also https://leanprover-community.github.io/contribute/tags_and_branches.html for more details.
