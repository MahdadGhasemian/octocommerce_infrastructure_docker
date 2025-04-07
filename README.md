# octocommerce_infrastructure_docker

```bash
ansible-playbook playbooks/check_connection.yml -i inventory.yml
ansible-playbook playbooks/setup.yml -i inventory.yml
```

# Web UI Tools

- [PgAdmin](https://pgadmin.octocommerce.ir/)
- [Rabbitmq UI](https://rabbitmq.octocommerce.ir/)
- [Redis GUI](https://redisinsight.octocommerce.ir/)
- [Minio UI](https://minio.octocommerce.ir/)

## Generate .htpasswd file for redis inside login page

```bash
htpasswd -c ./roles/services/files/.htpasswd admin
```

## Redis connection

- host: redis
- port: 6379
- username: leave it empty (default)
