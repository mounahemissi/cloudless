# CloudLess - Projet Cloud Auto-Hébergé

CloudLess est une solution de cloud souverain pour établissements scolaires basée sur :
- Nextcloud
- OnlyOffice
- MariaDB
- Nginx (reverse proxy)
- LDAP (authentification)
- Supervision (Zabbix, Grafana)
- Kubernetes ou Docker Swarm

## Déploiement

```bash
ansible-playbook -i inventory.ini site.yml
```
