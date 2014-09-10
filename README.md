## Ansibles - nodejs [![Build Status](https://travis-ci.org/Ansibles/nodejs.png)](https://travis-ci.org/Ansibles/nodejs)

Ansible role for installing nodejs, from package or by building it from source.


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher.
- Depends on Ansibles.build-essential


#### Variables

```yaml
nodejs_version: "0.10.26"           # nodejs version to install.
nodejs_install_method: "source"     # "package" or "source" or "binary"
```

For "unstable" node versions (0.11), you may wish to use "binary" if you don't want to compile from source:

```yaml
nodejs_version: "0.11.13"           # nodejs version to install.
nodejs_install_method: "binary"     # "source" or "binary" (package is not available for 0.11)
```

#### Thanks to
- [Manuel Tiago Pereira](https://github.com/mtpereira)


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ansibles/nodejs/issues)!
