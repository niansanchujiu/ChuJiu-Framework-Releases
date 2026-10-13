# ChuJiu 插件发行仓库

这里发布 ChuJiu（初九框架）的 WordPress 插件安装包和版本说明。

开发仓库保持私有。此仓库的 Git 提交只保留发行说明；插件 ZIP 包含运行所需的普通 PHP、CSS 和 JavaScript 文件。

## 安装与更新

1. 从 [Releases](https://github.com/niansanchujiu/ChuJiu-Framework-Releases/releases) 下载上传的 `chujiu.zip`。
2. 在 WordPress 后台选择“插件 → 安装插件 → 上传插件”，安装并启用 `ChuJiu`。
3. 后续可点击“立即更新”，或在插件列表选择“启用自动更新”。

插件目录为 `wp-content/plugins/chujiu/`。项目模板和自定义代码由各网站主题维护。

已有网站若开启了“禁止全站自动更新”，需要先关闭该设置，再选择插件自动更新。主机权限和 WordPress 计划任务会影响自动执行。

## 发行包

安装包使用 WordPress 官方 `@wordpress/scripts plugin-zip`，只收录插件运行文件、README 和包信息。开发依赖、Git 数据、测试以及 `blocks/`、`custom.example/`、`theme.json` 等主题开发参考不进入安装包。

稳定版本标签采用 `v版本号`，例如 `v1.0.6323`。请下载上传的 `chujiu.zip` 附件；GitHub 自动生成的 Source code 压缩包不是插件安装包。
