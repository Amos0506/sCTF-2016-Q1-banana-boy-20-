步驟1:下載圖片

步驟2:查看檔案格式

步驟3:使用hex編輯器分析檔案

步驟4:下載binwalk

步驟5:使用binwalk分析檔案

步驟6:使用dd抽出檔案
```
dd if=carter.jpg of=carter-1.jpg skip=140147 bs=1
```
```
dd if=圖片名稱 of=輸出圖片名稱 skip=跳過N塊後再開始複製 bs=M位元
```
