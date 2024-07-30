<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Vikunja

[![集成程度](https://dash.yunohost.org/integration/vikunja.svg)](https://ci-apps.yunohost.org/ci/apps/vikunja/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/vikunja.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/vikunja.maintain.svg)

[![使用 YunoHost 安装 Vikunja](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Vikunja。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Vikunja is a self-hosted open-source to-do list application for all platforms.

### Features

- Stay organized 
- Collaborate with peers
- Tasks  
- Kanban board
- CalDAV
- Links  

**分发版本：** 0.24.1~ynh2

**演示：** <https://try.vikunja.io/login>

## 截图

![Vikunja 的截图](./doc/screenshots/kanban.png)

## 文档与资源

- 官方应用网站： <https://vikunja.io/>
- 官方管理文档： <https://vikunja.io/docs/>
- 上游应用代码库： <https://kolaente.dev/vikunja/vikunja>
- YunoHost 商店： <https://apps.yunohost.org/app/vikunja>
- 报告 bug： <https://github.com/YunoHost-Apps/vikunja_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
或
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
