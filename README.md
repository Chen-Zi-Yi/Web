# Web
熟悉git使用流程
访问github被限制解决方案：
1.打开目录C:\Windows\System32\drivers\etc
2.更改hosts文件权限：鼠标右击hosts，打开属性，点击上方 安全，点击编辑权限，允许写入权限，确定。
3.用记事本打开hosts
4.在问价末尾输入
    #github
    52.69.186.44 github.com
    185.199.111.153 assets-cdn.github.com
    151.101.1.194 github.global.ssl.fastly.net
5.打开网站 http://ping.chinaz.com/
依次对这三个域名进行检测，选择延迟最低的IP地址，保存文件
6.打开cmd，输入ipconfig /flushdns 回车
7.接下来就可以顺利打开github.com了
