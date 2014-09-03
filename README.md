check_rds_replicationlag
========================

Nagios check for AWS RDS MySQL slave replication lag

usage: check_rds_replicationlag [-h] -d DBNAME -w WARNING -c CRITICAL [-r REGION]

optional arguments:
  -h, --help            show this help message and exit
  -d DBNAME, --dbname DBNAME
                        RDS DB name
  -w WARNING, --warning WARNING
                        Warning if lag is great than this many seconds
  -c CRITICAL, --critical CRITICAL
                        Critical if lag is great than this many seconds
  -r REGION, --region REGION
                        AWS Region - default is us-west-1
