<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 的 ChuWiki

[![集成程度](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![工作状态](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)

[![使用 YunoHost 安装 ChuWiki](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 ChuWiki。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

ChuWiki is first and foremost a wiki. A wiki is a website whose pages can be edited by the visitor. However, a history system allows you to track modifications made to a page and restore an old version of the page if necessary.

**分发版本：** 2.0~ynh3

**演示：** <http://chuwiki.genezys.net/wiki/Bac%20%C3%A0%20sable>

## 截图

![ChuWiki 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <http://chuwiki.genezys.net/>
- 官方管理文档： <http://chuwiki.genezys.net/>
- 上游应用代码库： <https://github.com/genezys/chuwiki>
- YunoHost 商店： <https://apps.yunohost.org/app/chuwiki>
- 报告 bug： <https://github.com/YunoHost-Apps/chuwiki_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
或
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
