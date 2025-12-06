```shell
# update dependency
go mod tidy
# increment the version in version/version.go
mage buildLinux
mage publishDocker
```
