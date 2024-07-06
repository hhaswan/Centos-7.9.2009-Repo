
After CentOS 7 end of life maybe you get error when update repo.
Last version **Centos 7.9.2009** (Same as my case)
Create file
`nano /etc/yum.repos.d/CentOS-Vault.repo`
Fill the file 

then create file 
`nano /etc/yum.repos.d/endpoint.repo`
fill the file then update with :
`yum update`
install git :
`yum install git`

```
Installing:
 git                             x86_64         2.43.0-1.ep7          endpoint
Installing for dependencies:
 git-core                        x86_64         2.43.0-1.ep7          endpoint
 git-core-doc                    noarch         2.43.0-1.ep7          endpoint
 pcre2                           x86_64         10.23-2.el7           C7.9.2009-base
 perl-Error                      noarch         1:0.17020-2.el7       C7.9.2009-base
 perl-Git                        noarch         2.43.0-1.ep7          endpoint
 perl-TermReadKey                x86_64         2.30-20.el7           C7.9.2009-base
```

>Reference [Endpoint](https://www.endpointdev.com/blog/2021/12/installing-git-2-on-centos-7/) and [Vault CentOS](https://vault.centos.org/7.9.2009/)
> Written with [StackEdit](https://stackedit.io/).
