# Azure CLI Fundamentals

## Overview

Azure CLI is a command-line tool used to manage and automate Microsoft Azure resources.

For cloud security professionals, understanding Azure CLI is valuable because it enables efficient management of cloud environments, security configuration checks, and automation of repetitive tasks.

This section documents common Azure CLI patterns and commands used when working with Azure resources.

---

# Azure CLI Command Pattern

Azure CLI follows the structure:

```
az <service> <verb>
```

Memory trick:

```
Azure → Service → Action
```

Examples:

```bash
az vm create

az vm start

az vm stop
```

---

# Common Azure CLI Examples

## Virtual Machines

```bash
az vm create

az vm list

az vm show

az vm start

az vm stop

az vm delete
```

## Resource Groups

```bash
az group create

az group list

az group show

az group delete
```

## Storage Accounts

```bash
az storage account create

az storage account list
```

---

# Common CLI Verbs

| Verb | Purpose |
|---|---|
| create | Create a resource |
| show | Display information about a resource |
| list | List multiple resources |
| update | Modify a resource |
| delete | Remove a resource |
| start | Start a resource |
| stop | Stop a resource |
| restart | Restart a resource |

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

Azure CLI can support security workflows by helping analysts:

- Review Azure resources.
- Audit configurations.
- Automate security checks.
- Investigate cloud environments.
- Manage security-related resources.

Examples:

- Reviewing virtual machine configurations.
- Checking resource deployments.
- Validating cloud security settings.

---

# Key Takeaways

Azure CLI provides security professionals with a practical way to interact with Azure environments and automate cloud operations.

Combined with scripting, Azure CLI can help improve efficiency and support cloud security investigations.