# terraform-repo

```
terraform init
terraform plan
terraform appy
```

### create terraform.tfvars file to store AWS credential and put it in .gitignore

```
$ cat terraform.tfvars
 AWS_ACCESS_KEY ="your access key"
 AWS_SECRET_KEY ="your secret key"$ ssh-keygen -f mykey
```

### Create your public private key pair and put them in .gitignore
```
$ ssh-keygen -f mykey
```
```
cat .gitignore
mykey*
terraform.tfstate
terraform.tfvars
terraform.tfstate.backup
```





