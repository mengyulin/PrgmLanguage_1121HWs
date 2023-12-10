# 作業 20

## 題目說明
依下列題意進行作答，輸入兩組城市字串，經串列操作後讓輸出值符合題意要求。

## 設計說明
由使用者輸入兩組英文城市名稱字串，城市間以逗號區隔，且均為小寫。
例如

    san francisco,boston,chicago,indianapolis 

與

    new york,los angeles,houston


將兩組字串依序存為串列一與串列二，並進行下列操作：

1. 將串列二加入串列一的尾端後，輸出串列。
2. 依堆疊形式移除一個城市，再依佇列形式移除一個城市，輸出串列。
3. 將串列進行排序後輸出。

## 輸入輸出
### 輸入說明
兩組英文城市名稱字串，城市間以逗號區隔，且均為小寫。

### 輸出說明
依上述操作後的城市串列。

### 範例輸入一

    san francisco,boston,chicago,indianapolis
    new york,los angeles,houston

### 範例輸出一

    ['san francisco', 'boston', 'chicago', 'indianapolis', 'new york', 'los angeles', 'houston']
    ['boston', 'chicago', 'indianapolis', 'new york', 'los angeles']
    ['boston', 'chicago', 'indianapolis', 'los angeles', 'new york']

### 範例輸入二

    kaohsiung,taoyuan,taipei
    chiayi,hsinchu,keelung

### 範例輸出二

    ['kaohsiung', 'taoyuan', 'taipei', 'chiayi', 'hsinchu', 'keelung']
    ['taoyuan', 'taipei', 'chiayi', 'hsinchu']
    ['chiayi', 'hsinchu', 'taipei', 'taoyuan']
