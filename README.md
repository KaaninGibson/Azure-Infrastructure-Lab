# Azure Infrastructure Administration Lab

Hands-on Azure infrastructure exercises covering compute, virtual networking, storage, access control, governance, monitoring, and resource cleanup. These are historical test-environment exercises, not a continuously deployed production architecture.

## Resource relationships

```mermaid
flowchart TD
    RG[Resource Group] --> VNET[Virtual Network / Subnet]
    RG --> VM[Azure Virtual Machine]
    RG --> NSG[Network Security Group]
    RG --> DISK[Managed Disk / Storage]
    VNET --> VM
    NSG --> VNET
    VM --> DISK
    RG --> MON[Monitoring and Alerts]
    RG --> GOV[RBAC / Policy / Locks]
```

## Recorded exercises

- Created resource groups, virtual networks/subnets, NSGs, a VM, and storage/disk resources.
- Reviewed role-based access control and Azure Policy settings.
- Configured or reviewed monitoring alerts and budget controls.
- Tested a resource lock and observed a `ScopeLocked` error.
- Used Azure CLI to export an inventory of nine resources.
- Performed resource-group teardown and checked for remaining resources.

## Evidence and limitations

See the [evidence matrix](docs/evidence-matrix.md) for the screenshots examined and what they demonstrate.

A September 9 screenshot shows the lab VM in **Stopped (deallocated)** state, supporting resource existence but not a running service. September 10 inventory screenshots do not independently verify connectivity, security posture, or every provisioning state.

**No raw Azure portal screenshots are published.** Subscription IDs, tenant IDs, public IPs, and other identifiers require redaction.

## Further validation

- Publish sanitized deployment screenshots and resource inventory output.
- Recover network connectivity/NSG validation results, if preserved.
- Add resource-lock and cleanup verification evidence.
- Publish exact commands or scripts only when recovered or independently tested.
