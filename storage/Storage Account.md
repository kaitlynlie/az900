# Storage Account

unique namespace for Azure Storage data accessible anywhere over HTTP/HTTPS

- locally redundant storage (LRS)
- geo-redundant storage (GRS)
- read-access geo-redundant storage (RA-GRS)
- zone-redundant storage (ZRS)
- geo-zone-redundant storage (GZRS)
- read-access geo-zone-redundant storage (RA-GZRS)

- Standard general-purpose v2:
    - Blob storage, queue storage, table storage, Azure files
    - LRS, GRS, RA-GRS, ZRS, GZRS, RA-GZRS
    - blobs, file shares, queues, tables
    - recommended for most scenarios
- Premium block blobs
    - Blob storage
    - LRS, ZRS
    - block blobs and append blobs
    - recommended for high transaction rates or use smaller objects or require consistently low storage latency
- Premium file shares
    - Azure files
    - LRS, ZRS
    - files shares only
    - recommended for enterprise or high-performance scale applications
    - supports both Server Message Block (SMB) and NFS file shares

## Storage account endpoints

unique namespace in Azure

naming rules:

- 3-24 characters and only contain numbers and lowercase
- unique within Azure

| **Storage service** | **Endpoint** |
| --- | --- |
| Blob Storage | https://<storage-account-name>.blob.core.windows.net |
| Data Lake Storage Gen2 | https://<storage-account-name>.dfs.core.windows.net |
| Azure Files | https://<storage-account-name>.file.core.windows.net |
| Queue Storage | https://<storage-account-name>.queue.core.windows.net |
| Table Storage | https://<storage-account-name>.table.core.windows.net |