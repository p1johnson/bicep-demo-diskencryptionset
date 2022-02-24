# Server-side encryption with customer-managed keys for new virtual machine
These templates demonstrate creating a new virtual machine with an encrypted managed disk using server-side encryption with customer-managed keys.
## Create Key Vault and Disk Encryption Set
This template creates a Key Vault and Disk Encryption Set used for server-side encryption.
### Bicep template
`encryptionset.bicep`
### ARM template
`encryptionset.json`
## Create virtual machine
This template creates a new virtual machine in a new virtual network using the previously created Disk Encryption Set for server-side encryption.
### Bicep template
`virtualmachine.bicep`
### ARM template
`virtualmachine.json`