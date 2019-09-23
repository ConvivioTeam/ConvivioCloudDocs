# Authentication

Authentication with Vault is handled through Github.

You will need to generate a personal access token and grant it `read:org` privilege. Save this token in you 1Password personal vault.

{% hint style="info" %}
DO NOT share your personal access token with anyone. Make sure to keep it safe.
{% endhint %}

To log in follow the instructions in the Vault [documentation](https://www.vaultproject.io/docs/auth/github.html#via-the-cli).

Currently Mike and Joe have full admin access to Vault. Additional team policies can be managed through Githubs teams and Vaults policy [asignment](https://www.vaultproject.io/docs/auth/github.html#configuration).

