# yarn tracking tool
To track how YARN using resource
Goals for tool:
- Portable
- Highly scalable
- Reliable
- Light

Current most compatible and setup notes:
- OS: CentOS 6.6
- Hadoop: HDP 2.4, admin HDFS user
- Slave nodes:
 - iotop
 - user with sudo permission
 - setup passwordless ssh for all nodes
- Master nodes
 - user with sudo permission
 - setup passwordless ssh for all nodes
