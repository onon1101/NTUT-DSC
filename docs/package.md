## 爲什麼需要兩次登入
在一開始進入 login.do 的網頁時, 我們會拿到4個cookie, 其中3個是session cookie , 且被賦予了httpOnly 的屬性, 故在js腳本中無法直接更改他.


![](./cookie.png)
圖：4個cookie (username是我自己加入的, 在此並沒有任何作用)
