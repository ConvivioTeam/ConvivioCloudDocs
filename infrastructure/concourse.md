# Concourse

[Concourse](https://concourse-ci.org/) is our CI of choice. There are two components to Concourse that you will need to become familiar with:

1. `fly` cli tool
2. [Web ui](https://concourse.convivio.cloud)

Please refer to existing build samples in the Agency App or on [Concourse Docs](https://concourse-ci.org/docs.html).

The key features of Concourse are:

* All builds are in docker containers
* The fly cli tool allows you to update the pipeline without pushing changes to a repo
* Integration with Cloud Foundry and Docker Hub.

