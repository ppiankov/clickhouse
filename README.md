# clickhouse
ansible playbook to rollout clickhouse cluster

update inventory/clickhouse-cluster.ini

# install keepers

ansible-playbook -i inventory/clickhouse-cluster.ini keeper.yml

# install clickhouse

ansible-playbook -i inventory/clickhouse-cluster.ini clickhouse.yml
