# Node

## Version manager

- nvm
- nodebrew
- ndenv(deprecated)
- nodenv

### nodenv

Using [homebrew](https://github.com/nodenv/nodenv).

```bash
$ brew install nodenv
```
done.


```bash
$ nodenv init
```
return 
```
# Load nodenv automatically by appending
# the following to ~/.bash_profile:

eval "$(nodenv init -)"
```

set to ~/.bash_profile

and then

```bash
$ source ~/.bash_profile
```

Verify tool

```bash
$ curl -fsSL https://github.com/nodenv/nodenv-installer/raw/master/bin/nodenv-doctor | bash
```

get

```bash
Checking for `nodenv' in PATH: /usr/local/bin/nodenv
Checking for nodenv shims in PATH: OK
Checking `nodenv install' support: /usr/local/bin/nodenv-install (node-build 4.4.5)
Counting installed Node versions: none
  There aren't any Node versions installed under `/Users/***/.nodenv/versions'.
  You can install Node versions like so: nodenv install 2.2.4
Auditing installed plugins: OK
```
Good.

try
```bash
$ nodenv install 10.15.3
```

Installed.
