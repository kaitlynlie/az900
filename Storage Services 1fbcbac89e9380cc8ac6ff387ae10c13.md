# Storage Services

Created: May 21, 2025 8:47 PM
Tags: am

## Blob: binary large object

files of any kind

three storage tiers:

hot - frequently accessed data

cool - infrequently accessed data

archive - rarely accessed data

## Queue Storage

small pieces of data (messages)

scalable async

## Table Storage

semi-structured data (NoSQL)

## File Storage

SMB protocol

file accessed via shared drive protocols

extend on-premise file shares/lift-and-shift scenarios

## Storage Account

group of services for blob, queue, table, file

highly scalable and durable

## Disk Storage

disk emulation

persistent storage for VMs

# Storage Services

Created: May 11, 2025 4:41 PM
Tags: storage

- Azure blobs: massive scalable object store for text/binary data, support for big data analytics
- Azure files: managed file shares for cloud or on-premies deployments
- Azure queues: messaging store for reliable messaging between application components
- Azure disks: block-level storage volumes for Azure VMs
- Azure tables: NoSQL table for structured, non-relational data

## Benefits

- durable and highly available: redundancy ensured data is safe if transient hardware failures occur
- secure: all data written is encrypted
- scalable
- managed
- accessible

## Azure Blobs

object storage solution for the cloud

unstructured

thousands of simultaneous uploads, massive amounts of data

doesn’t require devs to think about or manage disks

ideal for:

- serving images or docs directly to a browser
- storing files for distributed access
- streaming video and audio
- storing data for backup or analysis

### Storage tiers

- hot access: optimized for storing data is accessed frequently
- cool access: optimized for infrequent access data and stored for at least 30 days
- cold access: infrequently accessed and for at least 90 days
- archived access: rarely accessed and for at least 180 days

hot, cool, cold set at account level, archive not

all 4 set at bob level, during and after upload

data in cool/old can tolerate slightly lower availability

archive storage sores data offline and offers storage costs, but also highest costs to rehydrate and access data

## Azure Files

fully managed file shares in the cloud that are accessible via standard Server Message Block (SMB) or Network File System (NFS) protocols

- SMB: accessible from Windows, Linux, macOS / cached Windows Servers with Azure File Sync
- NFS: Linux, macOS

### Benefits

- shared access: support SMB and NFS
- fully managed: without need to manage hardware/OS
- scripting/tooling: powershell cmdlets and Azure CLI
- resiliency
- familiar programminng

## Azure Queues

storing large numbers of messages

each individual message ca be 64KB in size

backlog of work asynchronously

can be combined with Azure Function

## Azure Disks

block-level storage volume

same as physical disk but virtualized

## Azure Tables

large amount of structured data

NoSQL datastore that accepts authenticated calls

ideal for storing structured, non-relational data
