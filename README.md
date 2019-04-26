# Python課題 20190423

## 1. テストデータ生成

- `KEY`列: アルファベット大小混合ランダム3文字 + 数字ランダム5文字
- `X`列: アルファベット大小混合ランダム10文字
- `Y`列: 数字ランダム10文字

`KEY`列でソート。CSVで出力。

## 2. 偏差値計算

<img src="https://latex.codecogs.com/gif.latex?N" title="N" />をデータ数、<img src="https://latex.codecogs.com/gif.latex?x_i" title="x_i" />を各データとして、平均値<img src="https://latex.codecogs.com/gif.latex?\mu" title="\mu" />は

<a href="https://www.codecogs.com/eqnedit.php?latex=\mu&space;=&space;\frac{1}{N}&space;\sum^{N}_{i=1}&space;x_i" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mu&space;=&space;\frac{1}{N}&space;\sum^{N}_{i=1}&space;x_i" title="\mu = \frac{1}{N} \sum^{N}_{i=1} x_i" /></a>

標準偏差<img src="https://latex.codecogs.com/gif.latex?\sigma" title="\sigma" />

<a href="https://www.codecogs.com/eqnedit.php?latex=\sigma&space;=&space;\sqrt{\frac{1}{N}\sum^{N}_{i=0}&space;(x_i&space;-&space;\mu)^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sigma&space;=&space;\sqrt{\frac{1}{N}\sum^{N}_{i=0}&space;(x_i&space;-&space;\mu)^2}" title="\sigma = \sqrt{\frac{1}{N}\sum^{N}_{i=0} (x_i - \mu)^2}" /></a>

<img src="https://latex.codecogs.com/gif.latex?x_i" title="x_i" />の偏差値<img src="https://latex.codecogs.com/gif.latex?T_i" title="T_i" />は

<a href="https://www.codecogs.com/eqnedit.php?latex=T_i&space;=&space;\frac{10(x_i&space;-&space;\mu_x)}{\sigma}&space;&plus;&space;50" target="_blank"><img src="https://latex.codecogs.com/gif.latex?T_i&space;=&space;\frac{10(x_i&space;-&space;\mu_x)}{\sigma}&space;&plus;&space;50" title="T_i = \frac{10(x_i - \mu_x)}{\sigma} + 50" /></a>

