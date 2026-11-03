# Azure Governance, Monitoring and Cleanup

## Recorded exercises

- Reviewed Azure RBAC and Azure Policy.
- Configured or reviewed budget and monitoring alert settings.
- Tested a resource lock and encountered a `ScopeLocked` error.
- Exported an Azure CLI inventory reporting nine resources.
- Performed resource-group teardown and checked for orphaned resources.

## What the lock test demonstrates

A `ScopeLocked` response is evidence that a requested change was prevented by a lock at that scope. It is **not** proof of broad governance coverage or a full security assessment.

## Repeatable validation checklist

1. Confirm the active subscription and scope without publishing identifiers.
2. Inventory resource groups and resources.
3. Review least-privilege role assignments and policy compliance.
4. Check budgets and alert rule scopes.
5. Test a lock only against disposable lab resources.
6. Remove the lock when appropriate, tear down the lab, and verify resources are absent.
7. Check billing and unattached resources separately; deletion of a resource group alone does not prove zero cost.

The original exact CLI transcript has not been recovered in this repository. Avoid representing reconstructed commands as the original commands.
