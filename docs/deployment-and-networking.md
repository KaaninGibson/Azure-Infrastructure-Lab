# Azure Compute, Networking and Storage

## Recorded lab work

The historical Azure exercises include resource groups, a virtual network with subnets, network security groups (NSGs), an Azure virtual machine, and storage/managed disk resources.

A screenshot dated September 9 shows a lab VM resource in **Stopped (deallocated)** state. Later resource inventory screenshots show several Azure resource types. These are evidence of resource existence, **not** proof of an active workload or successful network connectivity.

## Administrative workflow

1. Plan resource-group boundaries and region selection.
2. Create a virtual network and subnet address spaces.
3. Apply an NSG with explicit inbound/outbound rules.
4. Provision a test VM and managed disk/storage resources.
5. Review effective network rules and test connectivity where evidence exists.
6. Inventory resources, inspect dependencies, and clean up to control cost.

## Evidence required for stronger claims

- Sanitized VM overview and deployment state.
- NSG rules and effective security rules.
- Connection test with source/destination context.
- Disk and storage association.
- Cleanup results showing remaining resource counts.

**Do not publish** subscription IDs, tenant IDs, public IPs, connection strings, or access keys.
