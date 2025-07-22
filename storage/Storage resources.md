# Storage resources

performance:

standard: general purpose v2

premium: block, page, files (blobs)

redundancy:

lrs locally redundant storage: 3 copies

zrs zone redundant storage: 3 copies spread over 3 availability zones

grs: async replicated in paired region, 3+3

zgrs: 3 copies spread each availability zone and async in paired region, 3+3

standard: all 4

premium: lrs and zrs

services:

blob: block blob

access tiers: hot, cool (30 days), cold (90 days), archive (offline, 180 days)

pay more hotter tier for capacity, pay more cooler for operations

page block: managed disk, pick type and cap

file block: SMB and NFS (premium only)

Azure File Sync: sync files between different locations

queues: FIFO, event driven

tables: key-value

static websites

lifecycle management: move and delete data, free

storage tasks: paid, more scale and capabilites