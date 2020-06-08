# documentation

1) restore estrewn-production-final-snapshot
2) select the db.r5.large DB instance class
3) select the estrewn-dbclustparamgroup DB cluster parameter group
4) select the estrewn-dbparamgroup DB parameter group
5) select the estrew-db-securitygroup
6) set the DB Instance identifier to "estrewn-production"
7) restore estrewn-production-instance-1-final-snapshot
8) start the estrewn browser machine
9) copy public DNS to SecureCRT session
10) copy the IPv4 Public IP address to the estrewn.com Record Set in Route 53
11) connect the estrewn browser server SecureCRT session
12) renew the certificate if necessary (sudo /usr/local/bin/certbot-auto renew --standalone --debug)
13) cd server
14) in root.py, set the server.socket_host parameter to the private IP address of the estrewn browser server machine
15) bash run_server.sh
