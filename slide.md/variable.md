title: Python - Variable
author:
  name: 咪路
  email: mail@mirumo.org
output: ./variable/index.html
style: ../main.css
--


<h1 style="font-size: 72px">
	Python - Variable
</h1>

## 資訊學院 / 咪路

--


<h1 style="font-size: 1.6em">
	數字
</h1>
## 整數 / 小數

--

### 數字的基本運算
- 加減法
	- 1 + 2
	- 3 - 4
- 乘除
	- 5 * 6
	- 7 / 8
	- 10 // 9

--

### 數字的基本的運算
- 次方
	- 2 ** 10
- 取餘數
	- 9 % 5

--

### Example

- print(2 ** 10)
- print(2 ** 10.0)
- print(6 / 2)
- print(6 // 2)

<p>What's different?</p>

--


<h1 style="font-size: 1.6em">
	字串
</h1>
## 'String' or "String"

--

### 基本的運算
- 字串的串接
	- 'Hello' + 'World'
- 字串乘法
	- 'Apple' * 3

--

### Example
- print('Hello' + ' ' + 'Python!')
- print('Python! ' * 3)

<p>How can i print <mark> I'm python. </mark></p>

--


<h1 style="font-size: 1.6em">
	跳脫字元
</h1>
## 特殊字元 \'

--

### Example

- print('I\'m Python!')
<table border="1" style="float: right;" cellpadding="10">
<tr><td>\'</td><td>單引號</td></tr>
<tr><td>\"</td><td>雙引號</td></tr>
<tr><td>\n</td><td>換行符號</td></tr>
<tr><td>\t</td><td>水平 tab 鍵</td></tr>
<tr><td>\v</td><td>垂直 tab 鍵</td></tr>
<tr><td>\b</td><td>退格鍵</td></tr>
</table>
<p><a href="https://www.w3schools.com/python/gloss_python_escape_characters.asp">more</a></p>

--


<h1 style="font-size: 1.6em">
	變數
</h1>

--

### 什麼是變數？

指在電腦記憶體裏存在值的被命名的儲存空間。
<img style="height:300px;margin: 20px auto;display: block" src="../images/variable-topic.jpg" />

--

### 可以想像成....

<p>一個盒子，裡面可以裝任何東西！</p>
<p>並且在盒子上貼上一個標籤，幫他取名字。</p>
<br/>
<p>命名的規則：A~Z a~z 0~9 或是底線(&lowbar;)。</p>
<p>不能數字開頭，不能是<a href="https://www.w3schools.com/python/python_ref_keywords.asp">保留字</a>。</p>

--

### 那麼盒子裡面可以裝什麼呢？

- 數字
- 字串
- 其他
	- True, False
	- None

--

<h1 style="font-size: 1.6em;">設定/宣告 變數</h1>
## 名稱 = 內容
## name = '咪路'

--

<h1 style="font-size: 1.6em;">顯示變數裡的值</h1>
## print(name)

--

### Practice

- 在一個變數當中存入自己的名字
- 並且輸出 Hi, OOO!
- 其中 OOO 是變數裡的值

