# 題目分類

我在本校的judge上挑了幾題跟課程內容有關的題目  
記得先 **登入** 才能答題XD

## 目錄

### 😏 高一期中考 - 抱佛腳專區

抱歉，for迴圈找不太到適合的題目  
請自己練習XD

還有，建議照順序做喔!

- [輸入,輸出以及變數](#io)
- [基礎運算](#calc)
- [if-else](#if-else)

### 🧐 高一期中考 - "我要拿高分"專區

- ["我要拿高分"專區](#high-score)

## 輸入,輸出以及變數 <a name = "io"></a>

- **純print()** - [a033: hello, world](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a033 "a033: hello, world")  
  
  這題敘述很長，反正就是印出hello, world就對了  
  
  ```python
  # 如果要印字串，記得用 "" 包起來
  print("你要的東西")
  ```

- **變數, print()** - [a001: 哈囉](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a001 "a001: 哈囉")  

  要注意輸出的格式  
  有時候寫錯是因為格式出問題

  ```python
  name = input()
  print("hello", name)
  # 會印出 hello(空格)名字
  ```

- **變數, print()** - [a007: K-I-S-S-I-N-G](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a007 "a007: K-I-S-S-I-N-G")  
  
  跟上一題蠻像的，加油 !

- **for迴圈, print()** - [a038: 我不說髒話](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a038 "a038: 我不說髒話")  

  記得`input()`讀進來是**字串**嗎?  
  用`int()`可以把**字串**轉成**整數**  

  ```python
  count = int(input())

  for i in range(count):
    print(i)
  # 會印出 0 1 2 ... count-1 (有換行喔)
  ```

## 基礎運算 <a name = "calc"></a>

- **純減法題** - [a014: 中華民國萬歲！](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a014 "a014: 中華民國萬歲！")  

  這題目讓我想到辣個男人

- **純除法題** - [a029: 分組報告](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a029 "a029: 分組報告")  

  python裡的除法(`/`)蠻神奇的  
  整數除整數的結果一定會是小數  
  不過用 `//` 可以只取除法的整數部分

  ```python
  print(3/1) # 輸出 3.0
  print(3//1) # 輸出 3
  ```

- **綜合題** - [a042: 買鉛筆](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a042 "a042: 買鉛筆")  

  上課時有做過類似的題目(吧)  
  取餘數用要 `%` 喔

- **綜合題** - [a015: 妳那裡現在幾點了？](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a015 "a015: 妳那裡現在幾點了？")  

  這題沒甚麼，就是要花點時間想解法  
  真的解不開就先跳過吧 !

## if-else <a name = "if-else"></a>

值得一提的是  
這部分有加 👌 的題目有 "不用`if`的解法"  
也許你可以挑戰看看  
不過我認為這些題目拿來當if-else練習還蠻適合的

- **純if-else題**👌 - [a019: 0 與 1](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a019 "a019: 0 與 1")  

  喚醒你對if-else的記憶

  ```python
  number = int(input())

  if number == 504:
    print('slap like now')
  elif number == 420: # python沒有else if, 是 elif
    print('yesssss')
  else: # else不能加條件喔
    print('smh')
  ```

  關於這題，強烈建議你試著想出一個不用if的解法  
  不會很複雜，而且答案超級有趣的喔😏

- **搭配取餘數 (`%`) 的 if-else題**👌 - [a020: ㄑㄧˊ 數？](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a020 "a020: ㄑㄧˊ 數？")  

  除2取餘數就可以判斷是奇數還是偶數了  
  對了，我都念奇數

- **搭配取餘數 (`%`) 的 if-else題** - [a023: 文文的求婚--續集 (1 行版)](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a023 "a023: 文文的求婚--續集 (1 行版)")

  這題在求"某年是否為閏年"，有點難(也許?)  
  總之閏年滿足 :  
    1. 被4整除
    1. 不被100整除
    1. 被400整除  
  
  沒有3條件同時滿足就是平年

- **搭配大於 的 if-else題**👌- [a017: BASIC 的 SGN 函數](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a017 "a017: BASIC 的 SGN 函數")

- **一堆條件的if-else題**👌 - [a031: 山六九之旅](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a031 "a031: 山六九之旅")  

  也許有的寫法會用到`elif`  
  或是直接一堆`if`  
  跑得動就好 owob

- **搭配計算的if-else題**👌 - [a024: 該減肥了！](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a024 "a024: 該減肥了！")

## "我要拿高分"專區 <a name = "high-score"></a>

- **巢狀for迴圈** - [c042: Shark-Ragu](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=c042 "c042: Shark-Ragu")  

  經典的考題 - 九九乘法表 !  
  需要兩層for迴圈而成為大家的惡夢

  *順帶一題*  
  python的`print()`其實有一些參數可以修改
  像是"sep", "end"

  ```python
  print(0,1,2)
  # 輸出 "0 1 2"
  
  print(0,1,2, sep='-')
  # 輸出 "0-1-2"
  
  print(0,1,2, end='')
  # 輸出 "0 1 2" 後 "不換行"
  
  print(0,1,2, sep='-', end='')
  # 輸出 "0-1-2" 後 "不換行"
  ```

- **痾...等差公式題?** - [a036: 我也愛偶數](http://judge-web.clhs.tyc.edu.tw/ShowProblem?problemid=a036 "a036: 我也愛偶數")

  可以用for迴圈一個一個加  
  也可以套公式  
  兩者執行效率差很多喔 !
