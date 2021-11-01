# Ansible checks Cisco Catalyst switches

Run common inspection commands for `Catalyst` switches.


## DevNet Code Exchange
This repository is featured on the Cisco DevNet Code Exchange.

[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/wafersystems/ios-check)



## Objectives
The playbook is used to inspect `Cisco Catalyst` series switches. The playbook and variable file define common catalyst inspection commands to be used for inspection. You can add, delete, or modify the command in the variable file as required.

## Requirements

To use this code you will need:
* `Linux` OS - Ex. `Red Hat` 7.0+, `Ubuntu` 18+, etc.
* `Python` 2.6+ or `Python` 3.5+
* `Ansible` 2.5+
* `SSH` client - `PuTTY`, `shell`,  `SecureCT`, etc.

## Install and Setupt
1. Install `Python` & `Ansible` softwared
2. Download ansible playbook files from `github`
3. Modify the `IP` address, `username` and `password` in the inventory file
4. Run the `ansible-play xxx.yaml --syntax-check` command to check the syntax
5. Run the `ansible-play xxx.yaml -C` command to dry run
6. Run the `ansible-play xxx.yaml > xxx.file` command to redirect the output
