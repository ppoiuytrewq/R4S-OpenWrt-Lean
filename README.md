# NanoPi-R4S 的 OpenWrt 固件  
基于 [Project OpenWrt | CTCGFW's Team](https://github.com/project-openwrt) 对 R4S 的适配对 [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede) 进行定制编译  

## 固件特性  
1. 设置主机名为 `NanoPi-R4S`  
2. 默认 LAN IP： `192.168.1.1`  
3. 默认用户、密码： `root` `无`  
4. 插件仅包含： `OpenClash` `SSRPlus` `Samba4网络共享`  
5. 重命名 `ShadowSocksR Plus+` 为 `SSRPlus`，并微调其设置首页内容  
6. 主题仅包含 `luci-theme-argon` 且删除主题底部文字  
7. 精简 LuCI 界面，移除 `软件包` `挂载点` `备份/升级`  
8. 提供 `EXT4FS` 和 `SQUASHFS` 两种类型固件  

## 感谢  
   感谢所有提供了上游项目代码和给予了帮助的大佬们
