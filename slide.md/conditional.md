title: Python - Conditional
author:
  name: 咪路
  email: mail@mirumo.org
output: ./conditional/index.html
style: ../main.css

--


<h1 style="font-size: 72px">
	Python - Conditional
</h1>
## 資訊學院 / 咪路

--

<h1 style="font-size: 1.6em">
	我也能讓程式轉彎嗎？
</h1>

--

### if ...

<code>
if (條件):
  do something
</code>

--

### if ... else ...

<code>
if (條件):
  do something...
else:
  do something...
</code>

--

### 條件
- a == b
- 1 > 2
- 3 >= 4
- 5 < 6
- 7 <= 8
- 9 != 0

--

### Practice
- 使用者輸入一個數
- 並且印出偶數或是奇數

--

### 複合條件

- and
- or

<code>
number = 5
if (number > 0 and number < 10):
  print('0~5')
</code>

--

### Practice

- 輸入年紀與BMI
- 如果成年以及體重適中，輸出 OK
- 否則輸出 not OK

PS: 體重適中(BMI: 18.5~24)

--

### 完整的身材判斷呢？
<p style="line-height:.7em;">
<code style="font-size:.6em;">
if (BMI < 18):
  print('體重過輕')
else:
  if (BMI >= 18 and BMI <=24):
    print('體重適中')
  else:
    if (BMI > 24 and BMI < 30):
      print('輕度肥胖')
    else:
      if (BMI >= 30 and BMI <= 35):
        print('中度肥胖')
	  else:
        print('重度肥胖')
</code></p>

--

### if ... elif ... elif ... else ...
<p style="line-height:.7em;">
<code style="font-size:.6em;">
if (BMI < 18):
  print('體重過輕')
elif (BMI >= 18 and BMI <=24):
  print('體重適中')
elif (BMI > 24 and BMI < 30):
  print('輕度肥胖')
elif (BMI >= 30 and BMI <= 35):
  print('中度肥胖')
else:
  print('重度肥胖')
</code></p>

--

### Practice

- 請使用者輸入一個分數
- 90 ~ 100 輸出 A
- 80 ~ 89 輸出 B
- 70 ~ 79 輸出 C
- 60 ~ 69 輸出 D
- 0 ~ 59 輸出 F
- 不是正常 0 ~ 100 輸出 Error
