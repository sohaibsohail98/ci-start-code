# Why should we use SSH with Git-hub

## SSH keys and Git-hub
### There are two methods to clone the repo

``` SSH AND HTTPS ```
- We have two types repos ```public repo``` 
- second is ```private repo```

### The steps we needed to do to add SSH keys: 

- Generate SSH keys on the local system: 

In terminal:

```
cd
ls -a
cd .ssh
ls
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
sohaibsohail
(enter) x2 (no passcode)
```

This public key will be generated. This needs to be copied and pasted in the specific repo. 

- go to your git-hub to the specific repo 
- click on settings and deploy keys 
- click on add deploy key
# It is essential to write descriptive names, sohaib-jenkins

Now the secured public key from your local system has been copied over to the repo.