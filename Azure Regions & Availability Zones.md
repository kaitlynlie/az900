regions: geographical area on the planet

all azure regions have a region pair but regions always have exactly one pair assigned

availability zone: 

regional feature

grouping of physically separate facilities

designed to protect from data center failures

if zone goes down others will continue working

not all regions supported, supported region has three or more zones

service categories:

zonal services: VMs, disks, etc., choose availability zones services deployed

zone-redundant: storage, SQL, etc.

### protects from region-wide disasters

### region pairs:

300 miles away from each other, natural disasters

paired with another region

resides in same geography

static and cannot be chosen

some have platform-provided replication

planned updates across pairs

### geographies:

discrete market

two or more regions

fault tolerant from region wide failures

each region belongs only to one geography