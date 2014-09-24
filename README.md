speedtest-result-generator
===============

各種惡搞 Speedtest.net的工具 XDDDD

Python版本：
------------------

* 作者：[Pc Chou](http://about.me/pcchou)
* 環境：Python 2
* 呼叫方法： `python srg.py 參數`
* 參數說明（請依照順序）：
  * normal或smart (smart會自動為您隨機輸出，給你最近似實際情況的數值)
  * 下載頻寬(kbps)
  * 上傳頻寬(kbps)
  * Ping值(ms)
  * (可選)[伺服編號](http://paste.ubuntu.com/8410453/) （[完整版本](http://www.speedtest.net/speedtest-servers-static.php)）
* 例如：`python srg.py normal 314150 926530 58979` 會產生出 （網址）

![真相](http://www.speedtest.net/result/3781272742.png)

* `python srg.py smart 100000 40000 6` 會產生出 （網址）

![真相](http://www.speedtest.net/result/3783836539.png)

Bash版本：
------------------

* 作者：[Denny Huang](https://github.com/denny0223) 、 [Pc Chou](http://about.me/pcchou)
* 環境：Bash
* 呼叫方法: `./srg.sh 參數`
* 參數說明（請依照順序）：
  * normal或smart (smart會自動為您隨機輸出，給你最近似實際情況的數值)
  * 下載頻寬(kbps)
  * 上傳頻寬(kbps)
  * Ping值(ms)
  * (可選)[伺服編號](http://paste.ubuntu.com/8410453/) （[完整版本](http://www.speedtest.net/speedtest-servers-static.php)）
* 例如：`./srg.sh normal 314150 926530 58979` 會產生出 （網址）

![真相](http://www.speedtest.net/result/3782546990.png)

* `./srg.sh smart 100000 40000 6` 會產生出 （網址）

![真相](http://www.speedtest.net/result/3783838355.png)

PHP版本：
------------------

* 作者：[Pc Chou](http://about.me/pcchou)
* 環境：PHP
* 呼叫方法：
  * func.php
    * 請先include本檔案，再用 `getImage(參數)` 函式呼叫。
  * url.php
    * 直接使用該檔案，用GET參數呼叫。
* url.php參數說明：
  * {mode} normal或smart (smart會自動為您隨機輸出，給你最近似實際情況的數值) (若為normal可不填此項)
  * {dlkbps} 下載頻寬(kbps)
  * {ulkbps} 上傳頻寬(kbps)
  * {pingms} Ping值(ms)
  * (可選)[伺服編號](http://paste.ubuntu.com/8410453/) （[完整版本](http://www.speedtest.net/speedtest-servers-static.php)）(srv)
* 例如：`http://yourdomain.org/url.php?dlkbps=314150&ulkbps=926530&pingms=58979` 會產生出（網址）

![真相](http://www.speedtest.net/result/3782546990.png)

* `http://yourdomain.org/url.php?dlkbps=100000&ulkbps=40000&pingms=6&mode=smart`

![真相](http://www.speedtest.net/result/3783848922.png)

* func.php範例code: [點窩](http://pastebin.com/P0Mqjr9R)
* 註：url.php沒有調用func.php，兩者分開，請安心使用。

VB.net版本：
------------------

* 作者：[海豹](http://about.me/seadog007)
* 環境：VB.net 2012
* 呼叫方法：安裝 Framework 4.5 並執行 (GUI)
