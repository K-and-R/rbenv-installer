# rbenv installer

This tool is used to install `rbenv` and some plugins.

**NB**: This was forked from https://github.com/fesplugas/rbenv-installer but that repo has since been removed.


## Requirements

- Git
- Curl


## Install

Install [rbenv] and friends by running:

```bash
    curl https://raw.githubusercontent.com/k-and-r/rbenv-installer/master/bin/rbenv-installer | bash
```

Plugins installed:

- [carsomyr/rbenv-bundler](https://github.com/carsomyr/rbenv-bundler)
- [sstephenson/rbenv-vars](https://github.com/sstephenson/rbenv-vars)
- [sstephenson/ruby-build](https://github.com/sstephenson/ruby-build)
- [sstephenson/rbenv-default-gems](https://github.com/sstephenson/rbenv-default-gems)
- [sstephenson/rbenv-gem-rehash](https://github.com/sstephenson/rbenv-gem-rehash)
- [K-and-R/rbenv-installer](https://github.com/K-and-R/rbenv-installer)
- [K-and-R/rbenv-bootstrap](https://github.com/K-and-R/rbenv-bootstrap)
- [rkh/rbenv-update](https://github.com/rkh/rbenv-update)
- [rkh/rbenv-whatis](https://github.com/rkh/rbenv-whatis)
- [rkh/rbenv-use](https://github.com/rkh/rbenv-use)

## Installing a Ruby

Install latest stable Ruby and make it global:

```bash
    rbenv install 2.6.3
    rbenv global 2.6.3
```

## Updating

Update `rbenv` and plugins provided by the installer running:

```bash
    rbenv update
```

## Bootstrap

If you are installing `rbenv` in Ubuntu you'll probably need to install
some required packages. You can use the provided [`bootstrap`](https://github.com/K-and-R/rbenv-bootstrap) scripts.

```bash
    rbenv bootstrap-ubuntu-18-04
```

## About rbenv

**rbenv** source code is available at <https://github.com/sstephenson/rbenv>

[rbenv]: https://github.com/sstephenson/rbenv
