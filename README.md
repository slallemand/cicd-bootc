# cicd-bootc
Demo repo for Github Actions based builds of bootc images

For RHEL, this example uses an activation key to get access to a subscription and a service account to get access to the terms based registry images. These are set up as secrets and variables scoped to the repo.

### Build status
[![Fedora 40 bootc image workflow](https://github.com/nzwulfin/cicd-bootc/actions/workflows/build_fedora_bootc.yml/badge.svg)](https://github.com/nzwulfin/cicd-bootc/actions/workflows/build_fedora_bootc.yml)
[![RHEL 9 bootc image workflow](https://github.com/nzwulfin/cicd-bootc/actions/workflows/build_rhel_bootc.yml/badge.svg)](https://github.com/nzwulfin/cicd-bootc/actions/workflows/build_rhel_bootc.yml)
