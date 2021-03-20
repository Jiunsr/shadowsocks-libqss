# shadowsocks-libqss
1
1，window 安装包管理工具
chocolatey 怎么玩？如下：

第一：@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

第二：Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

根据网络情况可能需要一分钟到几分钟不等，如果遇到超时失败之类的，重试一下，再不行自行翻越长城。

需要JDK？

C:\> choco install jdk8

需要JDK9？

C:\> choco install jdk9


需要最新版Chrome？

C:\> choco install googlechrome


需要IDEA?

C:\> choco install intellijidea-community


需要Git？

C:\> choco install git

---

windows 终端 输入 .bat 文件名和后缀+回车 运行批处理文件
