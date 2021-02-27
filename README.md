# Webapp_rule

![error](https://github.com/re4lity/Webapp_rule.yaml/blob/master/error.jpg)

exploitable 3rd-party web applications on a network

This file contains the application signatures - unique application path, version string, application name. 

网络上可利用的第三方Web应用程序

该文件包含应用程序签名-唯一的应用程序路径，版本字符串，应用程序名称。

# Format

The format is specified below:

```
#AppName: 'JBoss jmx-console'
#  - 'unique_app_path_1'
#  - 'unique_app_path_2'
#  - 'version string'
#  - 'exploit_path'
#  - 'creds' --> for smart brute-forcing
```
# References

- [https://github.com/0xsauby/yasuo](https://github.com/0xsauby/yasuo)
- [https://github.com/ywolf/F-MiddlewareScan](https://github.com/ywolf/F-MiddlewareScan)
