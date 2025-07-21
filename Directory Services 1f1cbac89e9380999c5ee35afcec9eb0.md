# Directory Services

Created: May 11, 2025 9:11 PM
Tags: identity

## Microsoft Entra ID

directory service that enables sign in and access to both Microsoft cloud applications

maintain on-premises Active Directory deployment

Microsoft’s cloud-based identity and access management service

control identity accounts

connecting Active Directory with Entra ID can protect suspicious sign-ins

### Features

- authentication: verifies identity to access applications and resources
- SSO: one username and password, single identity is tied to a user
- app management
- device management

to connect Entra ID with on-premise AD, use Microsoft Entra Connect to synchronize user identities

## Entra Domain Services

provides managed domain services such as domain join, group policy, lightweight directory access protocol (LDAP), kerberos/NTLM authentication

can run legacy apps that can’t use modern authentication methods, don’t want directory lookups to go back to an on-premises AD DS environment

when Microsoft Entra Domain Services managed domain, define unique namespace

two Windows Server domain controllers are deployed into selected Azure region, deployment of DCs is replica set

## Synchronized Information

managed domain is configured to perform one-way synchronization from Microsoft Entra ID to Microsoft Entra Domain Services

can create resources directly in managed domain, aren’t synchronized back to Microsoft Entra ID

in hybrid environment with on-premises AD DS environment, Entra Connect synchronizes identity information with Microsoft Entra ID, synchronized to managed domain