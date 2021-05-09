# a003 - 提款卡密碼

如果用python解的話，相較於c++有兩個部分比較難處理

- [輸入沒有限定資料數量](#01)
- [字元距離無法直接相減獲得](#02)

## 🤔 輸入沒有限定資料數量<a name="01"></a>

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

## 🤔 字元距離<a name="02"></a>

接下來遇到的問題是要如何計算 "字元距離"  
不過 "字元距離" 其實也只是將 "字元" 的ascii值相減後取絕對值而已

python不同於c/c++  
字元無法透過直接相減來取得ascii值的差  
這題我是利用內建的`ord()`來分別取得待相減的兩個字元之ascii值  
順帶一提，`chr()`可以把ascii值轉成字元

那接下來就相減再取絕對值就這題就被破解了，好耶(☞ﾟヮﾟ)☞
