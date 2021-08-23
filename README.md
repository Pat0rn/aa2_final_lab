# Ansible Tower

### Project
---
* Set-up Project
![Project](/lab_images/project.png)
### Credentials
---
* Openstack Authentication
![openstack](lab_images/credential_openstack.png)
* SSH Authentication
![ssh](lab_images/credential_ssh.png)

### Inventories
---
* Control Node Inventory
   > Use Control Node as a Host in order to provision

![control](lab_images/inventory_control.png)

* Openstack Inventory
![openstack](lab_images/inventory_openstack.png)
![openstack_host](lab_images/inventory_openstack_hosts.png)

### Templates
---
![template_view](lab_images/templates_view.png)
#### Infrastructure
* Provision Openstack Role
![provision](lab_images/06_provision.png)

* Check Connection Role
![check_connect](lab_images/07_check_connect.png)

* Network Config Role
![net_config](lab_images/08_net_config.png)

* Clean Up Role
![clean_up](lab_images/09_clean_up.png)

#### Multi-tier App
* Add Subscriptions Role
![add_sub](lab_images/11_add_sub.png)

* Provision Postgresql Role
![add_db](lab_images/12_add_db.png)

* Provision Flask Role 
![add_app](lab_images/13_add_app.png)

* Provision HA-Proxy Role
![add_lb](lab_images/14_add_lb.png)

* Smoke test Role
![smoke](lab_images/15_smoke.png)

### Workflow
---
* Single Click Nested Workflow
![single_click](lab_images/single_click.png)
* Infrastructure Provision Workflow
![infra](lab_images/infra_provision.png)
* Multi-Tier App Deploy Workflow
![app](lab_images/multi-tier_provision.png)