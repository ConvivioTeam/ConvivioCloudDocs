# Vault

[Vault](https://www.vaultproject.io/) is a secrets store, it integrates into the following key areas of our infrastructure:

* Concourse
* Terraform
* Ansible

If you need to store anything secret and integrate it into any of the above pipelines then chances are you need Vault.

Our vault can be accessed at [https://vault.convivio.cloud](https://vault.convivio.cloud)

### Concourse

Vault is automatically configured to grab variables from our vault store. All you need to do is configure your pipeline to read the correct path for your secret.

### Terraform

Terraform requires an approle access\_id and secret\_id. These are generated manually. In the future this will be built differently.

### Ansible

Ansible requires an approle access\_id and secret\_id. These are generated manually. In the future this will be built differently.

