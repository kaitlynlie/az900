# Defense-in-depth

Created: May 15, 2025 8:04 PM
Tags: identity

protect information and prevent it from being stolen by those who aren’t authorized to access it

### layers of defense-in-depth:

**physical security**: first layer of defense, access to buildings and controlling access to computing hardware

**identity and access**: controls access to infrastructure and change control, use SSO and MFA, audit events and changes

**perimeter**: distributed denial of service (DDoS) protection to filter large-scale attacks before they can cause denial of service for users, perimeter firewalls to identify and alert malicious attacks against networks

**network**: limits communication between resources through segmentation and access controls, deny by default, restrict inbound internet access/limit outbound access where appropriate, implement secure connectivity to on-premises networks

**compute**: secures access to VMs, implement endpoint protection on devices to keep systems patched and current

**application**: helps ensure that apps are secure and free of security vulnerabilities, store sensitive app secrets in secure storage medium

**data**: controls business and customer data that you need to protect, attackers are after:

- stored in database
- stored on disk inside VM
- stored in software as a service (SaaS) apps
- managed cloud storage