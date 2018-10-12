# openshift-admin
OpenShift administrations playbooks

## Requirements
```
ansible-galaxy install kwoodson.yedit
```


## Update authentication providers
```
ansible-playbook -i inventory.yaml roles/set_identity_providers.yaml
```

