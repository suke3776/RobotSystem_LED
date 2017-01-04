# Robosystem_LED
##動作
- `echo 1 > /dev/myled0` で2回連続の点滅を10回繰り返す。

##インストール方法
1. led　ディレクトリに入る
2. `make` 
3. `sudo insmod myled.ko`
4. `sudo chmod 666 /dev/myled0` 
