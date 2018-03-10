NSIS 重開機繼續安裝+自殺BAT[nsis reboot after install+ delete self of the bat]

	Google 搜尋關鍵字和網址
		nsis reboot after install
			HKLM\Software\Microsoft\Windows\CurrentVersion\RunOnce
			https://dotblogs.com.tw/howard/2011/09/02/35066
			https://dotblogs.com.tw/box5068/2011/05/17/25264
			http://blog.csdn.net/xt_xiaotian/article/details/6076251

		nsis registry

		bat 修改注册表

		nsis 啟動區
			http://blog.csdn.net/u012896330/article/details/72875285
			http://blog.sina.com.cn/s/blog_a60b1c3c0102xs2z.html
			

	自殺BAT-ping_delself.bat		

		ping 8.8.8.8

		ping 8.8.8.8

		ping 8.8.8.8

		ping 8.8.8.8

		REM 刪除捷徑
		del C:\Users\usernb\Desktop\123.lnk

		REM 刪除自己本身
		DEL %0
