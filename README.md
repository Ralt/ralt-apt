The repository holds the following files:

`conf/distributions`:

```
Origin: Ralt
Label: Ralt
Suite: stable
Codename: ralt
Version: 3.0
Architectures: amd64 source i386
Components: main
Description: Repository for ralt.
Update: - hipchat nodesource
```

`conf/updates`:

```
Name: hipchat
Method: http://downloads.hipchat.com/linux/apt
Architectures: amd64
VerifyRelease: blindtrust
GetInRelease: no
Components: main
Suite: stable

Name: nodesource
Method: https://deb.nodesource.com/iojs_2.x
Architectures: amd64
VerifyRelease: blindtrust
GetInRelease: no
Components: main
Suite: jessie
```
