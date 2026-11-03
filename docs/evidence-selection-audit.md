# Azure Infrastructure: evidence selection audit

This document records the curated evidence selection. Selected screenshot derivatives have now been uploaded to the repository; see the [published gallery](published-evidence-gallery.md). The original archives and unredacted images must remain private. Publication is not a guarantee that every small identifier has been cleared.

| Candidate | Supported observation / limit |
|---|---|
| Azure VM overview | Stopped/deallocated VM. |
| Resource lock | Delete lock present. |
| Resource lock CLI | CLI lock command/output; check command success. |
| Portal resource inventory | Visible resource types; not connectivity. |
| VNet and subnet inventory | CLI network resource properties; not connectivity. |
| Resource group properties | Resource group metadata. |
| RBAC assignments | Role assignments listed; not an access test. |
| Resource lock removal | No remaining locks at queried scope; not all scopes. |
| Azure CLI resource export | CLI inventory/export and resource count; not complete cost verification. |

## Publication standard

Only upload full-resolution derivatives after checking for user names, email addresses, tenant/subscription/device/object IDs, public IP addresses, hardware serials, recovery keys, secrets, and hidden metadata. A configuration screen is not proof of deployment, a script filename is not proof of execution, and an error is not proof of success.

## Excluded evidence

Duplicated inventory views, empty Drive Maps editor, unassigned or pending Autopilot profile states when presented as successes, and the zero-byte PowerShell script screenshot are not recommended as primary portfolio evidence. They can be documented as troubleshooting only when useful.

## Status

The image upload is complete for the selected set (9 published). The captions and selection notes have been reconciled with the uploaded filenames. Final independent full-resolution privacy certification is **not** claimed; a removed image may persist in Git history.
