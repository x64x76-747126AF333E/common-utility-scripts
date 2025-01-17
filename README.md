# common-utility-scripts
Common utility scripts to use with [Fugue](https://riskmanager.fugue.co).

- [env_creation_AWS_accounts.py](env_creation_AWS_accounts.py): Automate creation of Fugue environments for a list of accounts and regions
- [env_creation_AWS_org.py](env_creation_AWS_org.py): Automate creation of Fugue environments for a list of accounts and regions, extracted from AWS Organizations
- [env_creation_AZURE_subscriptions.py](env_creation_AZURE_subscriptions.py): Automate creation of Fugue environments for a list of Azure subscriptions with listed credentials
- [env_creation_AZURE_subscriptions_cli.py](env_creation_AZURE_subscriptions_cli.py): Automate creation of Fugue environments for a list of Azure subscriptions with listed credentials. Will ask for secret at command prompt instead of having them listed in the file as plain text
- [env_creation_Google.py](env_creation_Google.py): Automate creation of Fugue environments for a list of active Google projects, extracted from Google Organization
- [env_creation_AWS_govcloud_accounts](env_creation_AWS_govcloud_accounts.py): Automate creation of Fugue environments for a list of AWS GovCloud accounts and regions

For more information about Fugue, see [fugue.co](https://www.fugue.co) and [docs.fugue.co](https://docs.fugue.co).
