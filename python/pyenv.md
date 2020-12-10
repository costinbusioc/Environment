## Install pyenv and pyenv-virtualenv

```shell
brew install readline xz
brew install pyenv pyenv-virtualenv
```

Add this to .zshrc/.bashrc
```
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

## Usage

### Create virtualenv with specific version
```
pyenv virtualenv 2.7.10 my-virtual-env-2.7.10
```

### Create virtualenv from current version
```
pyenv version
3.4.3 (set by /home/yyuu/.pyenv/version)
pyenv virtualenv venv34
```

### Activate/Deactivate
```
pyenv activate <name>
pyenv deactivate
```

### Delete virtualenv
```
pyenv virtualenv-delete my-virtual-env
```
