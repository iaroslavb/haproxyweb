# Apache + haproxy testing

## HOWTO

### Instantiate nodes

```bash
cd vagrant
vagrant up
```

### Deploy software

```bash
cd ansible
ansible-playbook -i hosts site.yml
```

