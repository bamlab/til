# How to reuse argument from previous cmd in bash ?

* `!:n` is the n th argument of the previous command
* `!$` is the last argument of the previous command

For instance:
```shell
mkdir my_dir
cd !$
```
