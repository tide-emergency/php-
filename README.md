# php-
php免杀后门

由于5678.php存在后门，且测试发现该webshell不能过安全狗、D盾等安全设备，放在此处供大家进行分析。

1234.php，为删除后门的shll，功能和5678.php一样，是经过威盾加密生成，测试发现该后门可过d盾，但是过不了安全狗，安全狗仍然会提示存在加密后门。

code.php为菜刀一句话后门，测试发现可过安全狗；

jiemi_1.php和jiemi_2.php是对5678.php进行密码破解脚本，5678.php密码为hacker567 。

参考资料：https://www.uedbox.com/post/6109/，php 

Base64+Gzinflate在线解密：http://www.zhuisu.net/tool/phpencode.php

