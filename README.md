# Awesome Storage
A curated list of storage related tools and resources. Backups, redundancy, sharing, distribution, encryption, etc.

## Distributed file systems
Systems that expose a traditional file system interface with POSIX semantics.

* [Ceph file system](https://ceph.com/ceph-storage/file-system/) - Ceph’s file system runs on top of the same object storage system that provides object storage and block device interfaces. The Ceph metadata server cluster provides a service that maps the directories and file names of the file system to objects stored within RADOS clusters. The metadata server cluster can expand or contract, and it can rebalance the file system dynamically to distribute data evenly among cluster hosts. This ensures high performance and prevents heavy loads on specific hosts within the cluster.
