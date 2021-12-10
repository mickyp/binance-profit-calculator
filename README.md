# 幣安損益計算機 Binance Profit Calculator

## 功能列表
### 功能 1：顯示訂單中各交易對的買賣統整記錄

![image](https://user-images.githubusercontent.com/229322/145531544-db7849b6-0f4b-46fe-bc66-fec59fa6d05a.png)

### 功能 2：顯示所有交易對的帳面損益一覽表

![image](https://user-images.githubusercontent.com/229322/145531651-7ea5ac56-ca67-4925-b2cf-ee105b79ad7a.png)

### 功能 3：計算資金摘要，包含入金和當前帳面上總損益

![image](https://user-images.githubusercontent.com/229322/145531825-5aa88452-f557-4503-aa76-284e630e242c.png)


## 用法
1. 到幣安 App 或是網頁中找到 API 管理，並創建 API KEY。（請自行 Google 作法）
2. 將此 juypter notebook 檔案下載到本機
3. 開啟 [Google Colab](https://colab.research.google.com/)
4. 選擇 juypter 檔案上傳
![image](https://user-images.githubusercontent.com/229322/145533330-d1835d20-678f-4d81-bbe6-915d54436011.png)
5. 此時程式碼會開啟，請往下找到下列內容，並改成你自己幣安的 API KEY/SECRET
    ```
    api_key = '填入幣安的 api key'
    api_secret = '填入幣安的 api secret'
    ```
6. 找到下列內容並依樣畫葫蘆修改
    ```
    # 輸入你曾經有買賣過的交易對，可以輸入多組，每一組之間要換行

    # BTC/USDT 交易對
    bitcoinInfo('BTC', 'USDT')

    # ETH/USDT 交易對
    bitcoinInfo('ETH', 'USDT')
    ```
7. 選擇上方功能表 `執行階段` -> `全部執行`

![image](https://user-images.githubusercontent.com/229322/145533645-0e59c025-82e1-44c2-af3b-1086fc18e0aa.png)

8. 待執行完畢即可得知當前幣安損益一覽表了 💪 💯   
