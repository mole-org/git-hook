# git-hook

## Global Install

```sh
git clone https://github.com/mole-org/git-hook
cd git-hook
git config --global core.hooksPath $(pwd)
```

## For one repository install

```sh
git clone https://github.com/mole-org/git-hook
cd git-hook
pwd
# /Users/username/git-hook
cd <your code repository>
git config core.hooksPath <your git-hook path>
```

## Uninstall

```sh
git config --global --unset core.hooksPath
```

## Upgrade

```sh
git pull
```
