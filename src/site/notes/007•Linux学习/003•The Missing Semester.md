---
{"dg-publish":true,"permalink":"/007-linux/003-the-missing-semester/"}
---


# 第一讲 课程概览与shell
##### `ctrl`+`l`清屏快捷键
##### `<` `>` 重定向
	  `cat < t1.text > t2.text `  示例
##### `>>` 追加
##### `|` 管道符（取左边的输出作为右边的输入）
	  `ls -l | tail -n1`示例：输出最后一行
##### `sudo su`以超级用户登陆shell
##### `tee` 将输入传入文件并输出
##### `xdg-open`以合适的程序打开相应文件

# 第二讲 shell工具和脚本
#### 变量
eg:`foo=bar`
引用的时候用`$foo`
#### 字符串表示
#####  双引号`“` 会将其中的变量替换 
eg: `echo "value is $foo"`
	`value is bar`
#####  单引号`’` 直接输出 
