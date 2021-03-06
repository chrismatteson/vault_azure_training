## 8.0 HashiCorp Vault - Connect to Vault
Connect to Vault instance

### 8.0 Tasks
* Run commands from outputs to install and configure vault agent

## 8.1 HashiCorp Vault - Deploy Vault
Deploy and connect to Vault.

### 8.1 Tasks
* Initialize, Unseal, and Authenticate to Vault using the initial root token.
* View status of vault
* Lookup token information

https://learn.hashicorp.com/vault/getting-started/deploy  
https://www.vaultproject.io/docs/commands/status.html  
https://www.vaultproject.io/docs/commands/token/lookup.html  

`HINT 1: Copy the unseal keys and initial root token somewhere incase you need to use them again`

`Hint 2: If you connect to vault via SSH to the server, run export VAULT_ADDR=http://127.0.0.1:8200 to configure the vault connection`

## 8.2 HashiCorp Vault - Enterprise License
Enable Vault Enterprise features.

### 8.2 Tasks
* Write the license file provided by the Trainer into /sys/license
* Verify that vault license is installed

https://www.vaultproject.io/api/system/license.html  

`Hint 1: You can use the CLI to install the license. The command is vault write sys/license text=ASDFL08j...`
