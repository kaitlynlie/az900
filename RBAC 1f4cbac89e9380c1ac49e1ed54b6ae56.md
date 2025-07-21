# RBAC

Created: May 14, 2025 9:31 PM
Tags: identity

each role has associated set of access permissions that relate to that role

applied to a scope, which is a resource or set of resources that this access applies to

scopes:

- management group (collection multiple subs)
- single sub
- resource group
- single resource

hierarchical

enforced on any action initiated against Azure resource that passes through Azure Resource Manager: management service that provides a way to organize and secure cloud resources

uses an allow model, allows you to perform actions within the scope of that role