# a027 - 文文的求婚--續集 (EOF 版)

有時候會遇到題目敘述寫到:  
**"輸入以 EOF 作為結束"**  
或是 **"輸入有若干筆測試資料"**  
這時候我會用以下的方法讀資料

## CPP

```cpp
int in;

while(cin>>in){
  // do something
  cout << '\n';
}
```

其實也就這樣而已呢(☞ﾟヮﾟ)☞

## PYTHON

有兩種解決辦法：

### 1. while-loop 搭配 try except

```python
while True:
  try:
    line = input()
    # do something
    print()
  except:
    break
```

### 2. sys.stdin

```python
from sys import stdin

for line in stdin:
  # do something
  print()
```

我比較喜歡用第二種，因為相較第一種簡潔多了  
不過我比較常看到教學寫第一種就是了
