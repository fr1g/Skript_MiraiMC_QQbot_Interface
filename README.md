# Skript_MiraiMC_QQbot_Interface
Skript_MiraiMC_QQbot_Interface (SkMQi) is a Skript Interface to make MC Bukkit Server Owners to make their MiraiMC QQ bot Application Easy to be Customized.
btw：Simplified Chinese Language Only. Unless you use Q-ten-Q-cent rather than discord.

# 得了得了 咱不是洋鬼子嗷
# 强调一下 首先你得安装的有附属：Skript-logs
链接：https://github.com/Blueyescat/skript-logs 
### 我只测试过1.16.5 高版本不兼容的话找这位作者催更去。

嗯……在此感谢Skript交流群的佬们给我提供的帮助（尤其是zim！）还有SuperKRIPT的XPYEX（？是他吗 总之群马甲以前叫 那什么…… 穿山甲）向我极力安利reflect……
（“代码都给你了不会抄吗！”）
呜呜 我真的不敢用reflect……晚点一定晚点一定

然后就是吧 这个脚本有简单的处理冲突能力 但是弱的不行 建议别瞎折腾。
Repo里面有一个附属的示例。请尽可能按照里面的要求写你自己的功能。（忘了标注了 那个的重载指令是skr_reply 我以后的附属的重载都是这个风格 awa）
还有就是关于卡时间……不同服务器有不同服务器的情况 建议先跑一次timings 然后写功能 然后测试、卡时间、在接口代码里加点condition 以此提高整体功能的稳定性。
如果你为SkMQi写了一个很流批的附属 欢迎提交给我 提pr或发到邮箱： frigeso@icloud.com 都行。
**我直接欢迎大佬**

接口本体命令：输入/skmqi就知道有哪些了。
还有就是 模板的那个共鸣方法可能不太好 待高人指点awa
# 注意啊 on log如果你直接靠后台输出来debug的话会造成无止境的循环！ 不要轻易尝试！debug输出最好用log输出到文件 然后用浏览器打开！
（这样可以点刷新来重新查看log文件 老方便了。）
