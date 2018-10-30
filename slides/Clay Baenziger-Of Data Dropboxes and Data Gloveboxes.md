Resources from Clay Baenziger's Of Data Dropboxes and Data Gloveboxes:
* [Slides](http://clayb.net/presentations/Of%20Data%20Dropboxes%20and%20Data%20Gloveboxes.pdf)

References from talk:
* [Apache Atlas](https://atlas.apache.org/) - for preventing a data swamp; and providing data lineage
* [Dropbox HDFS Filter](https://github.com/cbaenziger/dropboxHDFSFilter) - to make WebHDFS into a data dropbox
* [Cluster Continuous Delivery with Apache Oozie](https://clayb.net/presentations/ApacheCon%20Oozie%20CD.pdf) - On ideas for arms-length continuous delivery on Apache Hadoop YARN clusters
* [Example pam_namespace configuration for per-user home and tmp directories](https://github.com/bloomberg/chef-bach/pull/1278) - A Chef configuration management language example using Bloomberg's [Chef-BACH](https://github.com/bloomberg/chef-bach) Hadoop reference deployment
* [YARN-7468 - Provide means for container network policy control](https://issues.apache.org/jira/browse/YARN-7468) - An implementation allowing per-user network policy controls. It uses Linux [net_cls](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/resource_management_guide/sec-net_cls) classification to tag each user's network traffic. One can then use [iptables](https://wiki.archlinux.org/index.php/iptables) to provide the various firewall rules.
