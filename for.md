# 繰り返し処理

## for文

for文は、条件を満たしていれば同じ処理を繰り返す
条件を満たさなければ、処理は終わる。

for文のきまり
for 変数　in range(繰り返す回数):
　　繰り返し中に実行する処理


for i in range(5):
    print(i)


## break

for i in range(5):
  if 条件：
　　　break


for i in range(5):
  if i== 3：
　　　break
  print(i)


==>  3になったら繰り返し処理終了

## continue文

continue文は、繰り返し処理である条件にあてはまったときに
処理をスキップしたい場合使用する。


for i in range(5):
  if i== 3：
　　　continue
  print(i)

==>  0.1.2.4と表示される

## ネスト（for文の中にfor文を入れる）

 for i in range(3): <== 外側0から2まで、1.外側から1回目の時は、内側は0~2
   for i in range(3):<== 内側0から2まで  2.内側のループが回り切ったら、外側が2回目のループに入る
     print(i,j,sep ="-")

==>   0-0

      0-1

      0-2
      
      1-0

      1-1

      1-2

      2-0 ...


  arr = [2 ,4, 6, 8, 10]
  for i in arr: <==iをarrに格納する
      print(i)
==> 2

    4
    
    6
    
    8
    
    10


  arr = [2 ,4, 6, 8, 10]
　sum = 0
  for i in arr: <==iをarrに格納する
      sum += i
      print(sum)

==> 30

