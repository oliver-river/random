# random
import random #一様分布のヒストグラムになる　＊正規分布に従うヒストグラムもある
b=0
for i in range(1200):
    a=random.randint(1,6)
    if a==1:
        b=b+1
print(b)
