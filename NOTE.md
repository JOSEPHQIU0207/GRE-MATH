# GRE MATH
-----
[数学句子翻译](数学句子翻译)<br>
[数学术语翻译](数学术语翻译)<br>
-----
#### 1.<br> 
#### **QA:** The least prime number greater than 24
#### **QB:** The greatest prime number less than 28
``` c++
for QA:28
for QB:23
therefore QA > QB chose A
"错误点：A是比24大的最小素数 B是比28小的最大素数"
```
#### 2.<br>
#### n is a positive integer,x = 7n+2 and y=6n+3
#### **QA:** The ones digit of x+y
#### **QB:** 5
```c++
for QA:x+y=13n+5
ones digit--->个位数
therefore 
when n=1: the ones digit of x+y=8
when n=3: the ones digit of x+y=4
therefore A ? B chose D
```

#### 3.<br>
#### During an experiment, the pressure of a fixed mass of gas increased from 40 pounds per square inch(psi). Throughout the experiment, the pressure, P psi, and the volume, V cubic inches, of  the gas varied in such a way that the value of the product PV was constant.
#### **QA:** The volume of the gas when pressure was 40 psi
#### **QB:** 1.2 times the volume of the gas when the pressure was 50 psi
```c++
题目分析：
当压力增大，gas:40 -> 50，P*V是一个常数
QA:当P=40,此时的V1
QB:当p=50,此时的1.2V2
if 设常数为X then V1=X/40 and V2=40V1*1.2/50
comparison QA and QB:
V2/V1 < 1 
therfore QA > QB chose A
```
#### 4.<br>
#### When the positive integer n is divided by 45,the remainder is 18. Which of the following must be a divsior of n>?
#### A.11   B.9 C.10 D.11 E.12
```c++
题目分析：
有一个正整数n,(n is divided by 45)->n/45,(remainder is 18)->n mod 45 = 18
if 设n=45k+18 then n=9(5k+2)
therefore n must is multiples of 9 chose B
```
#### 5.<br>
#### A construction company will produce identical metal supports in the shape of a right triangle with legs of length 3 feet and 4 feet. The three sides of each triangular support are to be constructed of metal stripping. If the company has a total of 6000 feet of metal stripping and there is no waste of material in the construction of the supports, what is the greatest possible number of supports that the company can produce?
#### A.428 B.500 C.545 D.600 E.1000
--------
###### 题目化简
###### ~~A construction company will produce identical metal supports in the shape of a right~~ triangle with legs of length 3 feet and 4 feet.~~The three sides of each triangular support are to be constructed of metal stripping. If the company has a~~ total of 6000 feet ~~of metal stripping and there is no waste of material in the construction of the supports,~~ what is the greatest possible number of supports that the company can produce?
--------
```c++
题目分析：
(right triangle)->直角三角形,(legs ...3 and ...4)->两条直角边分别为3，4
(total of 6000 feet)->一共有6000 feet,问做多可以做几个
Due to right triangle 3 and 4 thus get one triangles total need 3,4,5=3+4+5=12
therefore 6000/12=500 chose B
```
#### 6.<br>
####  A sequence of operations {A1, A2, ......, An} is defined as follows A1(x) = x, A2(x) = 2x2,......， An(x) = nxn. If A2 is performed on x, and then A4 is performed on the result, what is the final result?
#### A. 4x4 B. 8x4 C. 64x4 D. 64x8 E.4x8 (x后的数字为x的上标)
```c++
题目分析：
因为 对于这个数列，此时的x为A2
所以 A1(2X2)=2X2,
所以 An(X)=n(2X^2)^2
所以 A4=4(2X^2)^4=64X^8 chose D
"错误点：对于括号内的系数2要先算4次方在来和括号外的4相乘->2^4=16->16*4=64"
```
#### 7.<br>
#### **QA:** The length of a side of a regular pentagon with a perimeter of 12.5
#### **QB:** The length of a side of a regular hexagon with a perimeter of 15
```c++
题目分析：
每一条边的长度对于(regular pentag)->五边形 and (regualr hexago)->六边形
QA：12.5/5=2.5
QB：15/6=2.5
therefore A = B chose C
"错误点：翻译成求这两个图形的面积了，翻译不准确"
```
#### 8.<br>
#### **QA:** 32^3 * 2
#### **QB:** 32^2 * 65
```c++
32^3*2-32^2*65
=>32^2(32-65) , which is < 0
therefore A < B chose B
归纳：
两个数字/等式比较大小
QA/QB > 1 OR QA-QB > 0
```

#### 9.<br>
#### A clerk’s salary is $320 after a 25% raise. Before the clerk’s raise, the supervisor’s salary was 50% greater than the clerk’s salary. If the supervisor also receives a raise in the same amount as the clerk’s raise, what is the supervisor’s salary after the raise?
#### A. $370 B. $424 C.$448 D. $480 E. $576
```c++
题目分析：
(raise in the same amount)->增加相同的量
(raise in the same percentage)->增加相同的百分比
1.25X=320 -> X=256
256*1.5=384
384+(320-256)=448 chose D
"错误点：same amount 的意思不明白"
```

#### 10.<br>
#### The radius of circle A is 12 greater than the radius of circle B.
#### **QA:** The circumference of circle A minus the circumference of circle B. 
#### **QB:** 72
```c++
题目分析：
(A is 12 greater than B)->A 比 B 大 12 ==》 A = B + 12
therefore 24*3.14=75.36 > 72 chose A
"错误点：题目翻译错误"
```

#### 11.<br>
#### For a certain distribution, the measurement 12.1 is 1.5 standard deviations below the mean, and the measurement 17.5 is 3.0 standard deviations above the mean.What is the mean of the distribution?
```c++
题目分析：
A below B == B - A
therfore (12.1 is 1.5 standard deviations below the mean)=> 12.1 = Mean - 1.5SD
therfore
    12.1=M-1.5SD
    17.5=M+3S
M,S
"错误点:不知道 A below B的意思"
```
#### 12.<br>
#### If y is the average (arithmetic mean) of n consecutive positive integers, n>1, what is the sum of the greatest and least of these integers?
```c++
题目分析：
有n个连续的正整数，平均数是y,求最大和最小两个数的和
if 设 the first is X 
then the last is the X+(n-1)
根据求和公示：(n*(X+X+(n-1))/2 = ny
得到 2X+n-1 == X + X+(n-1) = 2y
"错误点:题目没有看完整，要求的是最大加最小，不是整个 数列的和"
```

#### 13.<br>
#### How many positive integers less than 100 have a remainder of 2 when divided by 13?
#### A. 6 B. 7 C. 8 D. 9 E. 10
```c++
题目分析：
根据选项 直接计算 发现
13*10 > 100
13*9 > 100
13** > 100
13*7 < 100



