# Vagrant box (Applicable on host only)
Helper to run box for ServerChef Virtual Machine

##  Instructions
```bash
# Start the virtual machine
$ vagrant up

# Add hosts to `/etc/hosts`:
$ sudo -c 'printf "192.168.33.10\tserverchef.local\tssh.serverchef.local\n" >> /etc/hosts'
```


