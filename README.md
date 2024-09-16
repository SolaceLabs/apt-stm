# [Solace STM ](https://github.com/SolaceLabs/solace-tryme-cli) APT repo

## Installation
1. add the SolaceLabs repo to APT

```
echo "deb [arch=amd64 trusted=yes] https://raw.githubusercontent.com/SolaceLabs/apt-stm/master stm main" | sudo tee  /etc/apt/sources.list.d/solace-stm-test.list
```

2. Install the latest version of STM

```
sudo apt-get update
sudo apt-get install stm
```
