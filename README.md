# Cisco交换机巡检

[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/wafersystems/ios-check)

通过Ansible进行Cisco批量巡检。

使用方法：

1. 修改和增加交换机信息

  在文件`inventory`中增加和修改交换机信息，包括`IP`，`登录名`和`密码`

2. 执行 
```
$> ansible-playbook ios-check.yaml
```
