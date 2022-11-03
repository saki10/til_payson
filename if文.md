# 条件分岐

1.順次進行
2.条件分岐
3.繰り返し

age = 22

## if文
 
if age >= 20:
    print("adault")

##  if~elif 文 条件を満たさない場合に使用する

if age >= 20:
   print("adult")
else:
   print("child")

## if ~ elif~else文 

if 条件A：
　条件Aを満たしたときの処理
elif 条件B:
　条件Bを満たしたときの処理
else:
　どちらの条件満もたさないときの処理

age = 0

if age >= 20;
    print("adult")
elif age == 0;
    print("baby")
else:
    print("child")


a > b：aはbより大きい
a < b：aはbより小さい
a >= b：aはb以上である（bの値も含む）
a <= b：aはb以下である（bの値も含む）
a == b：aとbは等しい
a != b：aとbは等しくない


## 文字列が含まれる分岐をしたいとき

a = 'hello python'
if 'aaa'in a:
   print('python')
else:
   print('other')


a > b：aはbより大きい
a < b：aはbより小さい
a >= b：aはb以上である（bの値も含む）
a <= b：aはb以下である（bの値も含む）
a == b：aとbは等しい
a is b ：aとbは等しい
a != b：aとbは等しくない
a is not b：aとbは等しくない
a in b：a はb に含まれる
a not in b ：a はb に含まれない


## 配列を条件分岐する場合、


s = 'orange'
l1 = ['apple', 'orange', 'grape']
l2 = ['onion', 'carrot', 'potato']
if s in l1 :　
  print('fruit')
elif s in l2 :
  print('vegetable')
else: 
  print('food')
