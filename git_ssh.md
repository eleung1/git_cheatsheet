GIT CHEATSHEET
==============

### Server using SSH key to hit git 
## Make sure remote.origin.url is using ssh: protocol
To check
```
git config --list
```

To set
```
git remote set-url origin ssh://git@your.gitrepo.com:7999/somename/project.git
```

## Bypass prompt for username/password:
```
ssh-agent bash -c 'ssh-add /var/lib/jenkins/.ssh/id_rsa; git fetch origin'
```




