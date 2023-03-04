
[scoop](https://scoop.sh/)是Windows的命令行安装程序

## QuickStart


打开PowerShell Terminal运行下列命令:

```sh
Set-ExecutionPolicy RemoteSigned -Scope CurrentUse

irm get.scoop.sh | iex
```



管理员身份安装
出于安全考虑，默认情况下已禁用管理员控制台下的安装。如果您知道自己在做什么，并希望以管理员身份安装 Scoop。请下载安装程序并在升级的控制台中使用-RunAsAdmin 参数手动执行它。下面是一个例子:

```sh
# download install scripte
irm get.scoop.sh -outfile 'install.ps1'


.\install.ps1 -RunAsAdmin -ScoopDir 'D:\package-manager\scoop' -ScoopGlobalDir 'D:\GlobalScoopApps' -NoProxy
```

