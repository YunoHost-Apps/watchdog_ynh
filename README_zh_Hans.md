<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Watchdog

[![集成程度](https://dash.yunohost.org/integration/watchdog.svg)](https://dash.yunohost.org/appci/app/watchdog) ![工作状态](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![使用 YunoHost 安装 Watchdog](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Watchdog。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**分发版本：** 5.16~ynh2
## 文档与资源

- 上游应用代码库： <https://sourceforge.net/projects/watchdog/>
- YunoHost 商店： <https://apps.yunohost.org/app/watchdog>
- 报告 bug： <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
或
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
