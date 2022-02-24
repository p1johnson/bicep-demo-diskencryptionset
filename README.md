# Server-side encryption with customer-managed keys for new virtual machine
These templates demonstrate creating a new virtual machine with an encrypted managed disk using server-side encryption with customer-managed keys.
## Create Key Vault and Disk Encryption Set
This template creates a Key Vault and Disk Encryption Set used for server-side encryption.
### Bicep template
`encryptionset.bicep`
### ARM template
`encryptionset.json`

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fp1johnson%2Fbicep-demo-diskencryptionset%2Fmain%2Fencryptionset.json)
## Create virtual machine
This template creates a new virtual machine in a new virtual network using the previously created Disk Encryption Set for server-side encryption.
### Bicep template
`virtualmachine.bicep`
### ARM template
`virtualmachine.json`

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fp1johnson%2Fbicep-demo-diskencryptionset%2Fmain%2Fvirtualmachine.json)