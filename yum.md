# Yum

## General Info
* the package manager for Oracle Linux
* works with **.rpm** files
* a RPM can contain a package or a list of repositories

### Common operations
#### Enable/Disable a repository
```bash
yum-config-manager --enable <repo-name>
yum-config-manager --disable <repo-name>
```

#### List all available versions of a package
```bash
yum --showduplicates list <package>
```
More info: ([link](https://unix.stackexchange.com/questions/6263/how-to-check-available-package-versions-in-rpm-systems))

#### Install specific version of a package
```bash
yum install <package name>-<version info>
```
More info: ([link](https://unix.stackexchange.com/questions/151689/how-can-i-instruct-yum-to-install-a-specific-version-of-package-x))
