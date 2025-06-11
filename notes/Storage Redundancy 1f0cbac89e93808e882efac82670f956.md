# Storage Redundancy

Created: May 10, 2025 9:47 PM
Tags: storage

stores multiple copies of data

## Redundancy in primary region

replicated 3 times in primary region

### Locally redundant storage

- replicates data three times within single data center in primary region
- 11 nines of durability 99.999999999% of objects over a year
- lowest-cost redundancy option, least durable
- protects against server rack and drive failures

### Zone-redundant storage

- replicates synchronously across three Azure availability zones in primary region
- 12 nines of durability 99.9999999999%
- accessible for read/write if zone unavailable

### Geo-redundant storage

- copies data synchronously three times within single physical location in primary region using LRS
- copies data asynchronously to single physical location in secondary region (region pair) using LRS
- 16 nines of durability 99.99999999999999%

### Geo-zone-redundant storage

- combines high availability provided by redundancy across availability zones with protection from regional outages provided by geo-replication
- copied across three Azure availability zones in primary region
- replicated to a secondary geographic region
- 16 nines of durability 99.99999999999999%