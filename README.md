

# Dwarf fortress playbook

_note: This project is not maintained_

## Cloud fortress

_[Ansible](http://docs.ansible.com) related._

1. Grab an _x64_ debian. PyLNP won't work on _x86_.
2. Authorize your ssh-key and permit root ssh login on the remote host
3. Play this playbook
4. Enjoy dwarf fortress


## How to play this playbook

### Create your inventory

```bash
echo '[df]
192.168.X.X' > hosts
```

### Play this playbook

```bash
ansible-playbook -i hosts df.yaml
```

### Play dwarf fortress

_within an X session, type this into a terminal:_

```bash
startlnp
```


## Next steps

* X11 forwarding
