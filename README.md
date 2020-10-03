# collection
An attempt to implement a comprehensive list of data structures and algorithms in Go inspired by the [Java Collection Framework](https://docs.oracle.com/en/java/javase/13/docs/api/java.base/java/util/Collection.html) using proposed design of Go generics.

## WARNING
This is an experimental package and is not ready to be used in production environment.

## Build
- Install go2 in your system if it is not installed already.
```shell script
cd ~/
git clone https://go.googlesource.com/go go2
cd go2
git checkout dev.go2go
cd src
./all.bash
```

- Move to this project and set the GOROOT to go2
```shell script
export GOROOT=~/go2/
```

- Build the app
```shell script
go tool go2go build 
```
