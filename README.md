# prest-serverless

prest-serverless 是一个帮助你快速发布 [pREST](https://github.com/prest/prest) 服务的模版.

## 需要
[安装 Serverless Devs Cli 工具](https://docs.serverless-devs.com/serverless-devs/install)

## 使用

```bash
# 首先克隆本仓库
git clone git@github.com:nangcr/prest-serverless.git
# 在本仓库根目录下的 code 目录中克隆 prest 仓库
cd prest-serverless/code
git clone --depth=1 git@github.com:prest/prest.git
# 修改 code 目录中配置文件
vim prest.toml
# 回到本仓库根目录并使用安装好的 Serverless Devs Cli 工具发布服务
cd ../
s deploy
```

## 配置
有关pREST的详细配置，请参考[https://docs.prestd.com/prestd/deployment/server-configuration/](https://docs.prestd.com/prestd/deployment/server-configuration/)

## License

Copyright (c) 2022-present [Nangcr](https://github.com/nangcr)

Licensed under [MIT License](./LICENSE)
