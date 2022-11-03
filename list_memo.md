python
# リストとは
## 変数は、１つのデータしか入らない

## リストは複数の変数を入れられるロッカーのようなもの


a = ["sato","suzuki","takahashi"]

print(a[0])
print(a[1])
print(a[2])

a=[["sato","suzuki"],["takahashi","tanaka"]]

print(a[0][0])
print(a[0][1])
print(a[1][0])
print(a[1][1])


変数をlistに変換
list(変数)

## print関数
 
end= ','
print('Hello',end=',')
print('World')

-->Hello,World

sep=''

print('Hello',sep='')
print('World')

-->Hello
-->World
