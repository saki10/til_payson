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


mylist = ["Apple", "Peach", "Orange"]
print(mylist)
--> ['Apple', 'Peach', 'Orange']

## 2 番目の要素を別の値と入れ替える
mylist[1] = "Grape"
print(mylist)
--> ['Apple', 'Grape', 'Orange']

## listを逆にする

org_list = [1, 2, 3, 4, 5]


org_list.reverse()
print(org_list)
-->[5, 4, 3, 2, 1]

fruits = [[['apple', 'orange'],['grape', 'banana']],['peach','strawberry']]
print(fruits[1][0])
-->peach

print(fruits[1][1])
-->strawberry

print(fruits[0][1])
-->['grape', 'banana']



