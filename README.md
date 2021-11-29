# Linux
linux筆記
Linux是一種自由開放原始碼的類似Unix 的作業系統，其廣泛運用於伺服器和嵌入式系統中。具有可移植性的Open Source的作業系統，它的程式碼可以被修改適合在各種機器上。運行目前主流的 Linux 發佈版本包括：Debian、Fedora、CentOS、Ubuntu 等
PING:常用網路檢測工具，可藉由發送 ICMP ECHO_REQUEST 封包，檢查自己與特定設備之間的網路是否暢通，並同時測量網路連線的來回通訊延遲時間（round-trip delay time）。
-n：參數指定封包數→EX：ping -n 10 blog.gtwang.org
-t：持續監看網路是否正常→EX：ping -t blog.gtwang.org
-4/-6：IPv4/IPv6
-c：指定Ping次數→EX：ping -c 4 blog.gtwang.org
-s：指定發送的數據字結數→EX：ping -s 1024 facebook.com
-i：指定收發資訊間隔時間→EX：ping -i 0.4 facebook.com
