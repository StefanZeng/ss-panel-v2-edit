# ss-panel-v2-edit
Welcome to the ss-panel-v2-edit wiki! 出自：http://www.qiaodows.com/phpzp/63.html
此程序基于 orvice的ss-panel v2.5.1修改。
修改内容：
1.将mailgun发邮件方式修改为smtp，并使重置密码功能支持smtp发信（必须要php支持smtp模块才能使用smtp发信，若用的是别人的虚拟主机请找管理员解决，若自己用vps或服务器搭建网站请安装smtp模块或者安装lnmp等网站环境）。
（此功能来自http://www.dou-bi.com/ss-jc22/，感谢原作者）
2.在管理用户界面加入 启用/禁用 按钮（即修改user表的switch和enable字段值），需要配合manyuser使用才能达到效果。
（本人自制）
3.在用户中心主页加入显示是否被禁用。
（本人自制）
4.解决一些细节问题。
（本人自改）

P.S. 若在此程序中发现原版未有的Bug，请及时与作者联系。作者QQ415372363。

题外话：此程序建议使用lnmp网站管理，因为lnmp默认安装nginx+php5.4+mysql5.5，比较适合此程序的运行，效率比较高。
以及v2和v3的简单对此：
1.php最低要求：v2-php54 v3-php55
2.界面：v2无法更改主题 v3可以
3.功能：没有什么差异，据说v3还删掉了一些功能（准确的说是没做出来，因为v3是重做的）
4.稳定性：v2已经是最终版，v3仍在更新，稳定性理论上还是v2好……
5.易用性：目前v2应该比v3好一点
6.易安装性：明显v2比v3容易……
