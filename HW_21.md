# 作業 21

## 題目說明
依下列題意進行作答，在程式中建立一篇文章中關鍵字出現次數的字典，
其「鍵」為關鍵字，「值」為出現次數。
再依要求排序關鍵字後輸出鍵與值。

## 設計說明
在程式中建立字典 d, 其「鍵」為關鍵字，「值」為出現次數:

    d = {'cut': 3, 'gully': 4, 'storm': 2, 'brook': 2}

再進行以下操作：

(1) 將鍵與值依規定之格式輸出：

    key {word} has value {number}

其中 {word} 為關鍵字，{number} 為其出現之次數。

(2) 將鍵存成串列。

(3) 依字母順序排列鍵之串列，並輸出鍵與值，格式同上。

(4) 依字母順序之反序排列鍵之串列，並輸出鍵與值，格式同上。

## 輸入輸出
### 輸入說明
無

### 輸出說明
依上述操作後的鍵與值。

### 範例輸出

    key cut has value 3
    key gully has value 4
    key storm has value 2
    key brook has value 2

    key brook has value 2
    key cut has value 3
    key gully has value 4
    key storm has value 2

    key storm has value 2
    key gully has value 4
    key cut has value 3
    key brook has value 2