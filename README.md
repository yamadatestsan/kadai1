# kadai1
This is a kadai1 repository.

コードは授業で作成したLEDを点灯させるコードをそのまま使用しています。
自分のオリジナリティーとしては、LEDをザクヘッドのモノアイ部分にはめこんで点灯させているところです。

#使い方
(1)$ https://github.com/yamadatestsan/kadai1.git
(2)$ cd myled/
(3)$ vi Makefile
(4)$ make
(5)$ vi myled.c
(6)$ make
(7)$ sudo insmod myled.ko
(8)$ sudo chmod 666 /dev/myled0
(9)LED点灯 & echo 1 > /dev/myled0
   LED消灯 & echo 0 > /dev/myled0

