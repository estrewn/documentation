# documentation

1) restore estrewn-production-final-snapshot
2) select the db.r5.large DB instance class
3) select the estrewn-dbclustparamgroup DB cluster parameter group
4) select the estrewn-dbparamgroup DB parameter group
5) select the estrew-db-securitygroup
6) set the DB Instance identifier to "estrewn-production"
7) restore estrewn-production-instance-1-final-snapshot
8) start ec2 browser machine
9) copy public DNS to SecureCRT session
10) connect the SecureCRT session
11) renew the certificate if necessary (sudo /usr/local/bin/certbot-auto renew --standalone --debug)
12) cd server
13) bash run_server.sh
