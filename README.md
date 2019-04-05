# ansible_mongo_shard_replication
1. modify host to fill in mongos, config server, replicat set (data mongod)
2. edit global variables on /group_vars/all 

##How to run
ansible-playbook -i host site.yml
