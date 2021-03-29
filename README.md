# Molecule Orb

[![CircleCI Build Status](https://circleci.com/gh/mtpettyp/molecule-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/mtpettyp/molecule-orb) [![CircleCI Orb Version](https://badges.circleci.com/orbs/mtpettyp/molecule-orb.svg)](https://circleci.com/developer/orbs/orb/mtpettyp/molecule-orb) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mtpettyp//master/LICENSE)

A simple CircleCI Orb for running [Molecule](https://molecule.readthedocs.io/en/latest/) tests.

### How to Contribute

We welcome [issues](https://github.com/mtpettyp/molecule-orb/issues) to and [pull requests](https://github.com/mtpettyp/molecule-orb/pulls) against this repository!

### How to Publish
* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from _feature branch_ to `main`.
* The title of the pull request must contain a special semver tag: `[semver:<segment>]` where `<segment>` is replaced by one of the following values.

| Increment | Description|
| ----------| -----------|
| major     | Issue a 1.0.0 incremented release|
| minor     | Issue a x.1.0 incremented release|
| patch     | Issue a x.x.1 incremented release|
| skip      | Do not issue a release|

Example: `[semver:major]`

* Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
* On merge, after manual approval, the orb will automatically be published to the Orb Registry.


