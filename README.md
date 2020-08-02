# MIUI12-精简计划

1.最近趁着卢本伟跳水入手一部K30P，到手发现MIUI12是很好用，但是开机就有300多个APP塞到我手机里，感觉很不爽，还是精简一下子吧！！

2.暂不提供脚本以实现批量操作，由于精简过度所以仅做参考，请点击链接自行查看。https://github.com/easonhawke/Miui12-Debloat/blob/master/Package.md

3.获取手机内部所有APK包名与路径，并保存为txt文档的ADB命令为adb shell pm list packages -f > xxx.txt。由于目前手机存储足够，所以实施精简操作时推荐禁用应用，而不是直接删除的方式。自行精简前请备份/data/system/users/0/package-restrictions.xml文件，如禁用导致无法开机，可试用Twrp等第三方Rec还原该文件。

4.维护人：@easonhawke

5.参与讨论方式：tg@easonn  email:easonn@88.com 
