# run
* `ansible-playbook -i inv deploy_rpm.yaml`
# check
* `ansible -i inv all -a 'ip a'`
# restart ceph daemons on all nodes
* `# ansible -i inv all -a 'systemctl restart ceph.target'`
