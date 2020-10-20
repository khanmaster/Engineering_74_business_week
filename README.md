# This is the guide to create git and github connection with SSH key
## Generate ssh key on localhost first
### create a github account

- copy the ssh key from localhost with 
```
cat id_rsa.pub
```
- paste the public key on your github in settings GPG SSH key option in your profile manue
- once saved go back to your terminal
- run the git hub command

```
git add .
git commit -m " msg"
git push -u origin main
```

- go back to github repo to verfiy the changes and connections

