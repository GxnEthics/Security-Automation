# Azure PowerShell Fundamentals

## Overview

Azure PowerShell is a module that allows administrators and security professionals to manage Microsoft Azure resources through PowerShell commands.

PowerShell is especially valuable within Microsoft environments because it integrates with:

- Windows systems.
- Active Directory.
- Microsoft Defender.
- Azure resources.
- Security automation workflows.

---

# Azure PowerShell Command Pattern

Azure PowerShell follows the structure:

```
<Verb>-Az<Service>
```

Memory trick:

```
Action → Azure Service
```

Examples:

```powershell
New-AzVM

Get-AzVM

Start-AzVM

Stop-AzVM

Restart-AzVM

Remove-AzVM
```

---

# Common Azure PowerShell Examples

## Virtual Machines

```powershell
New-AzVM

Get-AzVM

Start-AzVM

Stop-AzVM

Restart-AzVM

Remove-AzVM
```

## Resource Groups

```powershell
New-AzResourceGroup

Get-AzResourceGroup

Remove-AzResourceGroup
```

## Storage Accounts

```powershell
New-AzStorageAccount

Get-AzStorageAccount

Remove-AzStorageAccount
```

---

# Common PowerShell Verbs

| Verb | Purpose |
|---|---|
| Get | Read/View information |
| New | Create resources |
| Set | Change configuration |
| Remove | Delete resources |
| Start | Start resources |
| Stop | Stop resources |
| Restart | Restart resources |
| Update | Modify resources |
| Test | Validate/check |
| Invoke | Execute an action |

---

# Azure CLI vs PowerShell

| Task | Azure CLI | PowerShell |
|---|---|---|
| Create VM | az vm create | New-AzVM |
| View VM | az vm show | Get-AzVM |
| List VMs | az vm list | Get-AzVM |
| Delete VM | az vm delete | Remove-AzVM |
| Start VM | az vm start | Start-AzVM |
| Stop VM | az vm stop | Stop-AzVM |
| Restart VM | az vm restart | Restart-AzVM |

---

# Security Applications

Azure PowerShell can support security operations by helping professionals:

- Automate security checks.
- Collect information during investigations.
- Review Azure configurations.
- Manage security-related resources.
- Support incident response workflows.

Examples:

- Checking resource configurations.
- Gathering investigation data.
- Automating repetitive security tasks.

---

# Key Takeaways

PowerShell provides security professionals with a powerful automation capability, especially within Microsoft environments.

Developing Azure PowerShell skills supports efficient cloud administration, security monitoring, and Azure security operations.