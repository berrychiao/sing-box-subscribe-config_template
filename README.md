# sing-box-subscribe-config_template
For sing-box>1.13.0 and sing-box-subscribe

sing-box-subscribe将订阅链接转化为sing-box JSON格式配置文件的工具，原项目地址 https://github.com/Toperlock/sing-box-subscribe

本库下的sb-config-1.13.14tun.json是配置模版，下载放到 config_template 目录下选择使用，实现了tun模式以及mixed模式代理端口2080，以及Clash API（localhost:9090/ui）功能，以及GFW地区的较好的路由分流。

已经在SFM v1.13.14测试，无报错，无废弃参数警告。

ps.   brew install --cask SFM，其配置文件储存地址为 /Users/user/Library/Group Containers/xxxxxxxx.io.nekohasekai.sfavt/configs，与自己设置的配置名字不相同，存在映射关系，在上级目录的 settings.db 或 setting.db.wal 中储存。
