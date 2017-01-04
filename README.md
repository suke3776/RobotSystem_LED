# robosys_led
##動作
- `echo 1 > /dev/myled0` で10回点滅する。

##インストール方法
1. led　ディレクトリに入る
2. `make` 
3. `sudo insmod myled.ko`
4. `sudo chmod 666 /dev/myled0`
