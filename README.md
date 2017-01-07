# LEDによる2進数表示  
デバイスファイルに入力され0~9の10進数の値をLEDで2進数表示
## 実行コマンド例
`$ make  $ sudo insmod myled.ko  $ sudo chmod 666 /dev/myled0  $ echo <任意の値を入力> > /dev/myled0`
