# Cisco ios switch check

This is a simple example.

Batch inspection of Cisco switches using `Ansible`.

## DevNet Code Exchange
This repository is featured on the Cisco DevNet Code Exchange.

[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/wafersystems/ios-check)



## Run and test

1. Add switch info

  Modify the file `inventory`, replace `<host_ipx>`, `<username>`, `<password>`, and `<become_pass>`

2. Run 
```
$> ansible-playbook ios-check.yaml
```
