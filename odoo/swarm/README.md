# Odoo Swarm Deployment

## 📌 Note
Before install and configure your NFS server at:

```yaml
volumes:
  - /mnt/odoo/config/odoo.conf:/etc/odoo/odoo.conf:ro
  - /mnt/odoo/data:/var/lib/odoo
