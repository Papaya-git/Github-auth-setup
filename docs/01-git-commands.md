# 01 - Git commands

## Clone a repo

Use following commands (using X-exercises repo example):

```
git clone git@github.com:Papaya-git/C-exercises.git
```

## Push code to remote repository

Use following commands :

```
git add .
git commit -m "my message"
git push
```

## SSH key

use following commands : 

```bash
# generate ssh key of 4096bits with RSA algorithm
ssh-keygen -b 4096 -t rsa
```

```bash
# display public key content
cat /c/Users/Papaya/.ssh/key_name.pub
```

```bash
# add private SSH key to SSH agent
ssh-add ~/.ssh/key_name
``` 

