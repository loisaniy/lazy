# lazy
一个懒人自用的交易程序

方便自己看盘，交易期货&股票

将config.xml lazy.ini lazy.exe 放入同一个文件夹

启动lazy.exe后，会生成 lazy.db user.db signal.db 三个数据库

	lazy.db 内容为 当前客户端曾登陆过的 客户端账户
	user.db 内容为 曾登陆过的 资金账户
	signal.db 内容为 后台主动推送的 公有策略买卖信号

可用 Navicat for SQLite 查看内容

	账户：public 密码：123456 无期货/股票交易权限
	账户：test  密码：123456 有期货/无股票交易权限

若多人使用test账户，其中如果登陆期货账户，其他人登陆时，均能操作此期货账户，除非 第一次登陆的该期货账户登出

![image](https://github.com/loisaniy/lazy/imagelink/qq.png)

