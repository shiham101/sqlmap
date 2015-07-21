sqlmap
==


sqlmap 是一個開源的渗透测试工具，可以幫助自動化檢測SQL注入漏洞，獲取資料庫伺服器的權限。它具有功能强大的檢測引擎,針對各種不同類型資料庫的渗透测试的功能選項，包括獲取資料庫中儲存的資料，存取執行文件甚至可以通過外部資料庫連接的方式執行系统指令。

示範截圖
----

![截圖](https://raw.github.com/wiki/sqlmapproject/sqlmap/images/sqlmap_screenshot.png)

你可以訪問 wiki上的 [截圖](https://github.com/sqlmapproject/sqlmap/wiki/Screenshots) 查看各種用法的示範

安裝方法
----

你可以點擊 [這裏](https://github.com/sqlmapproject/sqlmap/tarball/master) 下載最新的 `tar` 打包的原始碼 或者點擊 [這裏](https://github.com/sqlmapproject/sqlmap/zipball/master)下载最新的 `zip` 打包的原始碼.

推薦你從 [Git](https://github.com/sqlmapproject/sqlmap) 倉庫獲取最新的原始碼:

    git clone https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

sqlmap 可以運行在 [Python](http://www.python.org/download/)  **2.6.x**  和  **2.7.x** 版本的任何平台上

使用方法
----

通過如下指令可以查看基本的用法及命令列参数:

    python sqlmap.py -h

通過如下的指令可以查看所有的用法及命令列参数:

    python sqlmap.py -hh

你可以從 [這裏](https://gist.github.com/stamparm/5335217) 看到一個sqlmap 的使用範例。除此以外，你還可以查看 [使用手册](https://github.com/sqlmapproject/sqlmap/wiki)。獲取sqlmap所有支援的特性、參數、命令列選項設定及說明的使用幫助。

連結
----

* 專案主頁: http://sqlmap.org
* 原始碼下载: [.tar.gz](https://github.com/sqlmapproject/sqlmap/tarball/master) or [.zip](https://github.com/sqlmapproject/sqlmap/zipball/master)
* RSS 訂閱: https://github.com/sqlmapproject/sqlmap/commits/master.atom
* Issue tracker: https://github.com/sqlmapproject/sqlmap/issues
* 使用手册: https://github.com/sqlmapproject/sqlmap/wiki
* 常見問題 (FAQ): https://github.com/sqlmapproject/sqlmap/wiki/FAQ
* 郵件討論列表: https://lists.sourceforge.net/lists/listinfo/sqlmap-users
* 郵件列表 RSS 訂閱: http://rss.gmane.org/messages/complete/gmane.comp.security.sqlmap
* 郵件列表歸檔: http://news.gmane.org/gmane.comp.security.sqlmap
* Twitter: [@sqlmap](https://twitter.com/sqlmap)
* 教學: [http://www.youtube.com/user/inquisb/videos](http://www.youtube.com/user/inquisb/videos)
* 截圖: https://github.com/sqlmapproject/sqlmap/wiki/Screenshots
