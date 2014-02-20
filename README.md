## 概要
3入力のうち、2入力以上を1にすることで、出力を1にする。

## 真理値表
| A | B | C | X |
|:-:|:-:|:-:|:-:|
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

## 論理式
真理値表より、正論理では以下の通り。  
![Positive Logic][1]

負論理で使用したい。  
![Negative Logic][2]

## 回路図
![Circuit Gate][3]
![Circuit][4]

[1]:https://dl-web.dropbox.com/s/wjeu89tjjs5v6fj/positivelogic.png
[2]:https://dl-web.dropbox.com/s/tkohlpltg4yf8po/negativelogic.png
[3]:https://dl-web.dropbox.com/s/gngfx2ldyzcpxt6/circuitGate.PNG
[4]:https://dl-web.dropbox.com/s/7p5exqgjvxknelm/circuit.PNG
