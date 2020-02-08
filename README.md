![](https://raw.githubusercontent.com/pystol/pystol-docs/master/assets/images/logo_readme.png)

**The open source, self-hosted and cloud-native fault injection platform**



| pystol  | pystol-galaxy | pystol-ansible | pystol-docs | quay.io | info |
|:-------:|:-------------:|:--------------:|:-----------:|:-------:|:----:|
| [![Docker image build](https://github.com/pystol/pystol/workflows/docker-image/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=docker-image) | | | [![Docs build](https://github.com/pystol/pystol-docs/workflows/jekyll-docs/badge.svg?event=push)](https://github.com/pystol/pystol-docs/actions?workflow=jekyll-docs) | [![Docker registry STAGING status](https://quay.io/repository/pystol/pystol-operator-staging/status "Docker registry STAGING status")](https://quay.io/repository/pystol/pystol-operator-staging) | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [![NodeJS install build](https://github.com/pystol/pystol/workflows/nodejs-install/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=nodejs-install) | | | | [![Docker registry STABLE status](https://quay.io/repository/pystol/pystol-operator-stable/status "Docker registry STABLE status")](https://quay.io/repository/pystol/pystol-operator-stable) | [![GitHub issues](https://img.shields.io/github/issues/pystol/pystol)](https://github.com/pystol/pystol/issues) |
| [![TOX ESlint build](https://github.com/pystol/pystol/workflows/tox-eslint/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=tox-eslint) | | | | | |
| [![TOX Flake8 build](https://github.com/pystol/pystol/workflows/tox-flake/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=tox-flake) | | | | | |
| [![TOX NodeJS units build](https://github.com/pystol/pystol/workflows/tox-nodeunits/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=tox-nodeunits) | | | | | |
| [![TOX Pytest build](https://github.com/pystol/pystol/workflows/tox-pytest/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=tox-pytest) | | | | | |
| [![TOX CheckTools build](https://github.com/pystol/pystol/workflows/tox-checktools/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=tox-checktools) | | | | | |
| [![E2E base install](https://github.com/pystol/pystol/workflows/e2e-deploy-base/badge.svg?event=push)](https://github.com/pystol/pystol/actions?workflow=e2e-deploy-base) | | | | | |


## Documentation

Please refer to the [official documentation](https://docs.pystol.org)
website for any information related to the project.

## CI dashboard

Pystol uses **GitHub actions**
and **badges** to run all the CI
tasks, the result of running these
tasks is represented using badges.

In particular we embrace the use of
CI dashboard as information radiators.

We created the [badgeboad project](https://badgeboard.pystol.org)
to show the value of any set of badges as a dashboard.

For more information you can open the
[CI dashboard](https://badgeboard.pystol.org)
directly or go to the
[project page in GitHub](https://github.com/pystol/badgeboard).

## Container images

All pystol official container images are hosted in Quay.io under
the [Pystol organization](https://quay.io/organization/pystol).

There you will find two repositories:

* The Pystol [staging repository](https://quay.io/repository/pystol/pystol-operator-staging).
Here you will find all the container images from the upstream end-to-end jobs from the GitHub
Actions jobs.

* The Pystol [stable repository](https://quay.io/repository/pystol/pystol-operator-stable).
Here you will find all the container images from the stable branches.

## License

Pystol is open source software
licensed under the [Apache license](LICENSE).
