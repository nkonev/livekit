```shell
# update dependency in go.mod
go mod tidy
# increment the version in version/version.go
mage buildLinux
mage publishDocker
```
