Ubuntu Package Backports
========================

[![ppa:mail6543210/backports](https://img.shields.io/badge/ppa-mail6543210/backports-informational.svg?logo=launchpad&style=popout)](https://gitlab.com/pjw91/ubuntu-backports/merge_requests)
[![Issues Welcome](https://img.shields.io/badge/Issues-welcome-brightgreen.svg?logo=gitlab&style=popout)](https://gitlab.com/pjw91/ubuntu-backports/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?logo=gitlab&style=popout)](https://gitlab.com/pjw91/ubuntu-backports/merge_requests)

[![PGP](https://img.shields.io/badge/pgp-0xC615247DB28DC1BF-blue.svg)](https://keyserver.ubuntu.com/pks/lookup?fingerprint=on&op=index&search=0x357578F3A41761CC1D9A22A9C615247DB28DC1BF)

This repo contains patches used to build package backports in [Launchpad](https://launchpad.net) [ppa:mail6543210/backports](https://launchpad.net/~mail6543210/+archive/ubuntu/backports).

The ppa contains some packages backported from the latest LTS version of Ubuntu to older LTS ones.

Packages are distributed in the hope that it will provide new features, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. Especially, there's **NO security updates** for the packages (Issues/PRs welcome).

The commit message MUST be in the form of `<package name> <package version> <Ubuntu version> <ppa version>`.
The 2<sup>nd</sup> field is the "upstream" Debian/Ubuntu version of a package being backported from; and the 3<sup>rd</sup> field is the corresponding numeric Ubuntu version.

The 4<sup>th</sup> field, ppa version, is in the form of `dd.dd.X`, where:

  1. `dd.dd` is the numeric Ubuntu version that a package is backported to,
  1. `X` is the build number.

The package version of a package in this ppa SHOULD be in the form of `<package version>~<ppa version>`.
