# RB_task1
---
## 課題内容

7,8回で作成したデバイスドライバーを改造しオリジナルのものを作る。
---
## 改造デバイスドライバーの解説

授業中に作ったデバイスドライバを改造し4つのLEDが光るようにした。
---
## コード

https://github.com/RouHishinuma/RB_task1/blob/master/myled1.c
---
## 使用した道具

1.ラスベリーパイ４x１

2.LEDx4

3.ブレッドボードx１

4.２２０Ω抵抗x4

5.ジャンパー線x8

---
## 使用方法
```
$ git clone https://github.com/RouHishinuma/RB_task1/blob/master/myled1.c
$ cd RB_task1
$ make
$ sudo insmod myled1.ko
$ sudo chmod 666 /dev/myled10
```
```
点灯
$ echo 1 > /dev/myled10
消灯
$ echo 0 > /dev/myled10
```
---
## 動画
https://youtu.be/HcrsSbrtwc4
