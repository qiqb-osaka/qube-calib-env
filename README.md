# qube-calib-env

## Caution

- Do not use `git add --update`
- Be careful in case updating submodules
  - Update only submodule version, not include modifications

## Setup

```
% git clone https://github.com/qiqb-osaka/qube-calib-env.git
% cd qube-calib-env
% pipenv install
% cd adi_api_mod
% make
% cd ..
```

## Run

```
% jupyter lab --ip=* --no-browser
```
