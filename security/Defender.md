# Defender

monitoring tool for security posture management and threat protection

monitors cloud, on-premise, hybrid, and multicloud environments to provide guidance and notifs

harden resources, track security posture, protect cyber attacks, streamline security management

easy, natively integrated to Azure

can automatically deploy a Log Analytics agent to gather security-related data

## Protections

- PaaS services: detect threats targeting Azure services and perform anomaly detection on Azure activity logs
- Data services: includes capabilities to help automatically classify data in SQL, get assessments for potential vulnerabilities with recommendations for how to mitigate them
- limit exposure to brute force attacks by reducing access to VM ports and using just-in-time VM access, can harden network by preventing unnecessary access

## Other clouds

- assesses AWS resources and includes the results in secure score
- Defender for Container extends container threat detection and advanced defenses to Amazon EKS Linux clusters
- Defender for Servers brings threat detection and advanced defenses to Windows and Linux EC2 instances

## Assess, Secure, Defend

continuously assess: know security posture, identify and track vulnerabilities

- continuously assess environment, includes vulnerability assessment solutions for VMs, container registries, SQL servers
- automatic, native integration with Microsoft Defender for Endpoint
- assessment tools, vulnerability scans

secure: harden resources and services with Azure Security Benchmark

- monitoring if new resources are configured according to security best practices
- if not, flagged and get a list of recommendations on what needs to be fixed

defend: detect and resolve threats to resources, workloads, services

- generate security alerts:
    - describe details of affected resource
    - suggest remediation steps
    - provide option to trigger logic app