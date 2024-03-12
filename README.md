# Awesome Storage
A curated list of storage open source tools. Backups, redundancy, sharing, distribution, encryption, etc.

## Distributed file systems
Systems that expose a traditional file system interface with POSIX semantics.

* [Ceph file system](https://ceph.com/ceph-storage/file-system/) - Ceph’s file system runs on top of the same object storage system that provides object storage and block device interfaces. The Ceph metadata server cluster provides a service that maps the directories and file names of the file system to objects stored within RADOS clusters. The metadata server cluster can expand or contract, and it can rebalance the file system dynamically to distribute data evenly among cluster hosts. This ensures high performance and prevents heavy loads on specific hosts within the cluster.

* [LeoFS](http://leo-project.net/) - LeoFS is a highly available, distributed, eventually consistent object/blob store. If you are searching a storage system that is able to store huge amount and various kind of raw data in its native format, LeoFS is suitable for that.

* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a general purpose storage system and covers most storage needs in a single deployment. It is open-source, requires no special hardware or kernel modules, and can be mounted on Linux, Windows and OS X.

* [OrangeFS](http://orangefs.com/) - OrangeFS is a software based scale-out parallel storage system.  It is ideal for large storage problems faced by HPC, BigData, Streaming Video, Genomics and Bioinformatics.

* [BeeGFS](https://www.beegfs.io/) - BeeGFS is the leading parallel cluster file system, developed with a strong focus on performance and designed for very easy installation and management. If I/O intensive workloads are your problem, BeeGFS is the solution.

* [Gluster](https://www.gluster.org/) - Gluster is a scalable network filesystem. Using common off-the-shelf hardware, you can create large, distributed storage solutions for media streaming, data analysis, and other data- and bandwidth-intensive tasks. Gluster is free.

* [HekaFS](http://pl.atyp.us/hekafs.org/) - CloudFS is a distributed fileysystem specifically intended to solve problems faced by a cloud provider when offering filesystem access “as a service” to cloud users (a.k.a. tenants).

* [JuiceFS](https://juicefs.com/en/) - JuiceFS is an open-source cloud-native distributed file system with high performance, commonly utilized in AI & machine learning for training, inference, model distribution, as well as in big data processing and analysis.

* [LizardFS](https://lizardfs.com/) - LizardFS Software Defined Storage is a distributed, parallel, scalable,
fault-tolerant, Geo-Redundant and highly available file system.

* [SeaweedFS](https://github.com/chrislusf/seaweedfs) SeaweedFS is a simple and highly scalable distributed file system. SeaweedFS can transparently integrate with the cloud. With hot data on local cluster, and warm data on the cloud with O(1) access time, SeaweedFS can achieve both fast local access time and elastic cloud storage capacity. 

* [Zenko](https://github.com/scality/Zenko) Zenko is the open source multi-cloud data controller: own and keep control of your data on any cloud.

## File sharing

* [Linshare](https://www.linshare.org/) - Linshare is an Open Source secure file sharing application intended to cover your business security and file transfer needs. If confidentiality and traceability are paramount for your business file transfers, then LinShare is your solution and better yet it's free ! We also offer high quality support services provided by our IT teams to suit your network at best.

* [Seafile](https://www.seafile.com) - Seafile is an open source file sync&share solution designed for high reliability, performance and productivity. Sync, share and collaborate across devices and teams. Build your team's knowledge base with Seafile's built-in Wiki feature.

* [ProjectSend](https://www.projectsend.org/) - ProjectSend is a self-hosted application (you can install it easily on your own VPS or shared web hosting account) that lets you upload files and assign them to specific clients that you create yourself! Secure, private and easy. No more depending on external services or e-mail to send those files!

* [Aurora Files](https://afterlogic.org/aurora-files) - Aurora Files is an open-source file storage platform for small teams and personal users.

* [ownCloud](https://owncloud.org/) - With over 50 million users worldwide, ownCloud is the market-leading open source software for cloud-based collaboration platforms. As an alternative to Dropbox, OneDrive and Google Drive, ownCloud offers real data security and privacy for you and your data.

* [Nextcloud](https://nextcloud.com/) - Nextcloud Files enables enterprises to take back control over their data, ensuring compliance, security and instant availability wherever their employees are.

* [Pydio](https://pydio.com/) - Modern file management platform built according to your business needs and regulations, Pydio is open-source software deployed on your servers or wherever you decide.

* [YouTransfer](http://www.youtransfer.io/) - YouTransfer is a simple but elegant self-hosted file transfer & sharing solution. It is an alternative to paid services like Dropbox and WeTransfer by offering similar features but without limitations, price plans and a lengthy privacy policy. You remain in control of your files. 

## Backups, replication, distribution
Software that handles backup and high availability of information, independent from the storage itself.

* [Amanda](http://amanda.zmanda.com/) -  Amanda is the most popular open source backup and recovery software in the world. Amanda protects more than a million servers and desktops running various versions of Linux, UNIX, BSD, Mac OS-X and Microsoft Windows operating systems worldwide.

* [BackupPC](https://backuppc.github.io/backuppc/) - BackupPC is a high-performance, enterprise-grade system for backing up Linux, Windows and macOS PCs and laptops to a server's disk. BackupPC is highly configurable and easy to install and maintain.

* [backy](https://github.com/vdbsh/backy) - Tiny multiprocessing utility for file backups.

* [Bacula](https://www.bacula.org/) - Bacula is a set of Open Source, computer programs that permit you (or the system administrator) to manage backup, recovery, and verification of computer data across a network of computers of different kinds.

* [Bareos](https://www.bareos.org/en/) - Bareos is a 100% open source fork of the backup project from bacula.org. The fork is in development since late 2010, it has a lot of new features.

* [Borg](https://github.com/borgbackup/borg) - BorgBackup (short: Borg) is a deduplicating backup program. Optionally, it supports compression and authenticated encryption.

* [Duplicacy](https://github.com/gilbertchen/duplicacy) - Duplicacy is a new generation cross-platform cloud backup tool based on the idea of Lock-Free Deduplication.

* [Duplicati](https://www.duplicati.com/) - Free backup software to store encrypted backups online. For Windows, macOS and Linux.

* [ElkarBackup](https://www.elkarbackup.org/) - ElkarBackup is a free open-source backup solution based on RSync/RSnapshot.

* [Kopia](https://github.com/kopia/kopia) - Kopia is a simple, cross-platform tool for managing encrypted backups in the cloud. It provides fast, incremental backups, secure, client-side end-to-end encryption, compression and data deduplication.

* [Restic](https://restic.net/) - Open Source easy to use single binary backup tool with encryption, dedupe, and supports object storage backends.

* [UrBackup](https://www.urbackup.org/) - UrBackup is an easy to setup Open Source client/server backup system, that through a combination of image and file backups accomplishes both data safety and a fast restoration time.

* [Zenko](https://www.zenko.io/) - Zenko is Scality’s Open Source Multi-Cloud Data Controller. Zenko lets you be in control of your data and leverage the efficiency of private and public clouds.

* [Backup Anything](https://github.com/gui-text/backup-anything) - Backup Anything are 100% open-source scripts for creating backup of databases and cloud buckets. Can be used on CI/CD or local.

## S3 compatible file servers
File servers that expose S3 compatible APIs

* [MinIO](https://min.io/) - A high performance, distributed object storage server, designed for large-scale data infrastructure. It is an ideal S3-compatible replacement for Hadoop HDFS and scale out NAS for machine learning and other big data workloads.

* [Ceph file system](https://ceph.com/ceph-storage/file-system/) - Ceph’s file system runs on top of the same object storage system that provides object storage and block device interfaces. The Ceph metadata server cluster provides a service that maps the directories and file names of the file system to objects stored within RADOS clusters. The metadata server cluster can expand or contract, and it can rebalance the file system dynamically to distribute data evenly among cluster hosts. This ensures high performance and prevents heavy loads on specific hosts within the cluster.

* [LeoFS](http://leo-project.net/) - LeoFS is a highly available, distributed, eventually consistent object/blob store. If you are searching a storage system that is able to store huge amount and various kind of raw data in its native format, LeoFS is suitable for that.

* [RIAK S2](https://riak.com/products/riak-s2/) - Riak® S2 is a highly available, scalable, easy-to-operate object storage software solution that’s optimized for holding videos, images, and other files. It provides simple but powerful storage for large objects built for private, public, and hybrid clouds.

* [OpenIO](https://www.openio.io/) - OpenIO SDS is an open source object storage solution ideal for Big Data, HPC and AI. With its distributed grid architecture and unique self-healing technology, OpenIO scales easily without mandatory data rebalancing, while delivering consistent high performance. OpenIO is S3 compatible and can be deployed on-premise or cloud-hosted, on any hardware that you choose.

* [Openstack Swift](https://docs.openstack.org/swift/latest/) - Openstack Swift is an autonomous object storage system part of the OpenStack Project. Swift is feature complete, is designed to integrate well with the OpenStack ecosystem, and emphasizes configurability and extensibility. It supports the S3 API but also provides its own, more complete, API which already benefits from the work done by its substantial community.

* [Garage](https://garagehq.deuxfleurs.fr/) - Garage is a hacker-oriented object storage software: it runs on every machine and through the regular Internet.
The key enablers to achieve these properties are its consensus-less design and its Rust close-to-the-metal implementation.
Garage is S3 compatible and honors the same consistency properties as Amazon S3.
It can host static websites and stands as a backend for any S3-compatible applications like Nextcloud.

* [lakeFS](https://github.com/treeverse/lakeFS/) - lakeFS is an open source tool that transforms your object storage into a Git-like repository. It enables you to manage your data lake the way you manage your code.

* [SeaweedFS](https://github.com/chrislusf/seaweedfs) SeaweedFS is a simple and highly scalable distributed file system. SeaweedFS can transparently integrate with the cloud. With hot data on local cluster, and warm data on the cloud with O(1) access time, SeaweedFS can achieve both fast local access time and elastic cloud storage capacity. 

## Cloud Sync Engine
Starting in Windows 10, version 1709, Windows provides the cloud files API. This API consists of several native Win32 and WinRT APIs that formalize support for cloud sync engines, and handles tasks such as creating and managing placeholder files and directories. Users of this API are typically sync providers and to some extent, Windows applications.

* [cfapiSync](https://github.com/styletronix/cfapiSync) - Working c# Example implementig a Cloud Sync Engine on Windows 10 / 11 based on the cloud files API. This is very early alpha.

## Contributions welcome
If you wish to contribute to this list, just fork, make your changes and send me a pull request, I'll be happy to review all of your suggestions :)

## Check out also

* [Awesome Cyber Security](https://github.com/okhosting/awesome-cyber-security/) - A curated list of cyber security resources and tools. 
