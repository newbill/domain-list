## 部署方式
- 使用 **Github Pages** 部署
    - `fork`[本项目](https://github.com/newbill/domain-list)到自己仓库，拉取仓库到本地。
    - 更改一下`img`文件夹里的图片和`_config.yaml`配置文件，并将更新后的文件送到仓库。
    - 最后开启`Github Pages`并绑定自定义域名，过一会就会自动生效。
- 使用 **Vercel** 部署（**推荐**）
    - 去 [Vercel](https://vercel.com/) 创建个`Vercel`账号，推荐选择`Github`登录。
    - 点击[快速部署](https://vercel.com/new/clone?repository-url=https://github.com/newbill/domain-list)，然后`Vercel`会在`Github`为我们自动创建仓库。
    - 在成功部署的`vercel`项目设置中新增一个`Hook`，并添加到`Github`对应仓库中。
    - 更改一下`img`文件夹里的图片和`_config.yaml`配置文件，并将更新后的文件送到`Github`仓库。
    - 喝杯咖啡，`Vercel`会自动拉取`Github`并更新部署，过一会就会生效了。

## 两种效果

- [小标签](https://midian.vercel.app)
- [纯文本](https://mibiao.vercel.app)

## License

[MIT](https://github.com/newbill/domain-list/blob/main/LICENSE) © 2022 - present [NEWBILL](https://github.com/newbill)