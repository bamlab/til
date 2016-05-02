# How to change remote in git ?

To see the list of remote URLs :
```shell
$ git remote -v
```

To add a remote URL:
```shell
$ git remote add REMOTE_NAME URL
```

To set a remote URL:
```shell
$ git remote set-url REMOTE_NAME URL
```

for instance:
```shell
$ git remote set-url origin https://github.com/USERNAME/OTHERREPOSITORY.git
```

* Source: https://help.github.com/articles/changing-a-remote-s-url/
