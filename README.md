# N2 airframe 
![](perspective.png)
![](N-2rocket.PNG)

## CFD result
計算条件

- 風速 150m （N-2ロケットの最大値）
-  レイノルズ数 1.5e7

### 抗力係数 Cd

#### 胴体のみ
Cd=0.54

![](CFD/Only_bodytube/Cd_0.54.png)

圧力分布
![](CFD/Only_bodytube/tube_pressure.png)
速度分布
![](CFD/Only_bodytube/tube_velocity.png)

#### フィンを配置したとき
（※計算条件として軸対称を指定しているので、厳密に3次元的な配置を再現できているわけではない。実際にはもっと抗力係数は低い）

Cd=3.89

![](CFD/With_fin_360deg/Cd_3.89.png)

圧力分布
![](CFD/With_fin_360deg/pressure.png)
速度分布
![](CFD/With_fin_360deg/velocity.png)

