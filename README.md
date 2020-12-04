# kadai1
This is a kadai1 repository.

コードは授業で作成したLEDを点灯させるコードをそのまま使用しています。
自分のオリジナリティーとしては、LEDをザクヘッドのモノアイ部分にはめこんで点灯させているところです。

# 使い方 
以下の(1)~(6)の手順で動作します

(1)リポジトリを複製する $ git clone https://github.com/yamadatestsan/kadai1.git

(2)ディレクトリを移動 $ cd myled/

(3)コンパイル $ vi Makefile $ make $ vi myled.c $ make
             
(4) モジュールをロード $ sudo insmod myled.ko

(5)権限を与える $ sudo chmod 666 /dev/myled0

(6)LED点灯 $ echo 1 > /dev/myled0  
   LED消灯 $ echo 0 > /dev/myled0

