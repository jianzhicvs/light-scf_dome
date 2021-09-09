简致云 light-scf 模板

# 模版说明

## 文件结构

Node.js

```
|-- Nodejs6.10_helloworld    文件夹名称| 语言_实例名
|   |-- config.json          模版配置文件，用于控制台模版详情展示，必填。
|   |-- server.json      函数配置文件，用于控制台解析模版函数配置，必填。
|   |-- README.md            模版使用说明，建议填写。
|   |-- src                  模版函数代码，文件及代码放置该目录下，以便服务中心解析。
|       |-- index.js         函数入口文件，必填。
|       `-- node_modules     依赖包，非必填。
```

Python

```
|-- Python2.7_helloworld     文件夹名称| 语言_实例名
|   |-- config.json          模版配置文件，用于控制台模版详情展示，必填。
|   |-- server.json       函数配置文件，用于控制台解析模版函数配置，必填。
|   |-- README.md            模版使用说明，建议填写。
|   |-- src                  模版函数代码，文件及代码放置该目录下，以便服务中心解析。
|       |-- index.py         函数入口文件，必填。
```

Php
```
|-- Php7.2_helloworld        文件夹名称| 语言_实例名
|   |-- config.json          模版配置文件，用于控制台模版详情展示，必填。
|   |-- server.json       函数配置文件，用于控制台解析模版函数配置，必填。
|   |-- README.md            模版使用说明。
|   |-- src                  模版函数代码，文件及代码放置该目录下，以便服务中心解析。
|       |-- index.php        函数入口文件，必填。
```


## 模版配置文件 config.json 说明
注意：
1. config.json 应当填写一个代码存储仓库
2. server.json 应根据当前开发者环境配置参数填写
```sh
{
    "scf-info": {
        "name": "通过API发送邮件",
        "describe": "本示例基于node8.9 nodemailer实现邮件发送",
        "middleware": "配置API转发即可",
        "author": "简致云"
    },
    "language": "Nodejs",
    "version": "8.9",
    "warehouse": {
        "github": "",
        "gitee": ""
    }
}
```

## 函数配置文件 server.json 说明


```YAML

 ```
 
