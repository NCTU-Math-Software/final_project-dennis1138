# Project 5-2 : 任意給定平面上三點, 判斷外心是否在三角形內.

## input

```
  在螢幕上用滑鼠點三個點 
```


## output

* 1.三角形 

* 2.外心

* 3.外接圓

* 4.判斷外心是否在三角形內部

## 作法

**1. 按下run，開出一個[-30 30]×[-30 30]的坐標軸

2. 螢幕上用滑鼠點三個點 

```
[X,Y]=ginput(3)
```

>判斷所選三點是否為共點或共線，如果是則從新輸入

3. 求外心座標

```
* 求垂直平分線

* 算出其中三角形其中兩邊的中點

* 並求三角形兩邊垂直平分線的斜率

* 利用中點和斜率得到垂直平分線

* 求出兩條垂直平分線的交點
```

4.求外接圓的半徑

將圓心與三角形其中一點的距離算出來，即可得到半徑

5.分別畫出三角形、外心、外接圓

6.判斷外心是否在三角形內部

將外心與三角形其中兩點所圍成的三角的面積算出來
總共會有三塊小三角形面積
比較三塊小三角形面積與原三角形面積
如果相等則在內部，反之，則在外部











