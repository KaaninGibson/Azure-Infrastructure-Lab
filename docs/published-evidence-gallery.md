# Azure Infrastructure Lab — Published Screenshot Gallery

These images were uploaded by the lab owner. Captions describe the observed evidence without implying production readiness or completed validation that the images do not establish. **Publication does not mean a new independent full-resolution privacy audit has been completed.** If any image contains a sensitive identifier, remove it from GitHub and its history as appropriate.

## 1. Azure virtual machine

![Azure virtual machine](01_Azure_VM_Overview.png)

VM resource overview; deallocated state is not running compute.

## 2. Resource lock

![Resource lock](02_Resource_Lock.png)

Resource lock configuration at capture time.

## 3. Azure CLI resource-lock operation

![Azure CLI resource-lock operation](03_Resource_Lock_CLI.png)

Command/output; interpret success from visible result.

## 4. Azure resource inventory

![Azure resource inventory](04_Resource_Inventory_Portal.png)

Resource existence; not service reachability.

## 5. Virtual network and subnet inventory

![Virtual network and subnet inventory](06_VNet_Subnet_Inventory.png)

Network objects, not proven connectivity.

## 6. Resource group properties

![Resource group properties](07_Resource_Group_Properties.png)

Resource-group metadata.

## 7. Role-based access assignments

![Role-based access assignments](08_RBAC_Assignments.png)

Azure CLI role-assignment query and column headers are visible, but the cropped output does not show a complete role assignment; no effective access test is proven.

## 8. Resource-lock removal check

![Resource-lock removal check](09_Resource_Lock_Removal_Check.png)

Observed lock status at queried scope.

## 9. Azure CLI resource export

![Azure CLI resource export](10_Azure_CLI_Resource_Export.png)

Azure CLI resource-list command writes JSON and a file listing is visible; the screenshot does not independently verify the number of exported resources, cost, or complete cleanup.

## Evidence boundaries

Screenshots of configurations, inventories, report-only evaluations, pending states, or command attempts must not be described as end-to-end successful deployments. Original unredacted archives are not intended for public release.
