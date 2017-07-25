### 什麼是Github.com？什麼是Github Desktop? 

這裡我們用非程式設計者懂的說法來解釋，故不符合它們原始的完整定義。  

- Github.com: 一個【雲端空間】讓你儲存備份用 

- Github Desktop: 安裝在你電腦上的【備份小精靈】，透過他，你可以選擇將某個資料匣裡的東西備份在自己電腦，或進一步備份在Github.com雲端空間。

我們先假設你已經在Github.com（以下簡稱.com）註冊了一個帳號，也在你電腦安裝了Github Desktop（以下簡稱Desktop），並把Desktop設定好可以和你的.com帳號連結。  

### Github使用需知   

- 「先」在.com開好未來電腦所要備份的資料匣（稱為repo）名稱（此時你電腦還沒有那資料匣），「之後」才透過Desktop來幫你在電腦上開對應的資料匣。   

- 在.com，你除了自己開一個新的資料匣外，你也可以把別人公開的資料匣複製一份到自己的帳號裡－－這裡的複製動作稱為「Fork」。

###### 練習一：複製別人的資料匣  
> 請連去tpemartin使用者的[「Minicourse-Github-Desktop」](https://github.com/tpemartin/Minicourse-Github-Destkop) repo, 然後點`Fork`把該資料匣完全複製到你的帳號裡。  

### 在自己電腦產生對應.com某個repo的資料匣  

當你完成練習一後，我們接下來可以在你電腦裡產生同樣內容的資料匣。  

- 請叫出Desktop備份小精靈，依以下圖示步驟在你電腦產生相同內容的資料匣。 

![image](/GIF/Desktop複製com資料匣.gif)

- 當你依照上面步驟進行後，你的電腦應該有一個名叫Minicourse-Github-Desktop的資料匣。 

### 備份電腦上的資料匣在自己電腦上 （Commit） 

這個動作叫Commit。

乍聽之下這是件很奇怪的事，即然資料匣已經在自己電腦上，那還需要備份在自己電腦上嗎？  

這是個合理的問題。的確，如果你的硬碟壞了，備份當然也沒了。然而，Github的備份其實不只是備份，他會留下一個歷史版本，之後你如果繼續修改資料匣內的內容，那一天想回到上個月備份的資料匣內容，你還是可以透過備份小精靈【坐時光機】回去那個時點。

- 請在你電腦裡的Minicourse-Github-Desktop資料匣，做任何內容變更，如修改裡面的檔案，或加、刪一個檔案，接著依照以下的步驟進行備份（在下面的步驟，我已經在該資料匣新增了一個data-wrangling-cheatsheet.pdf檔）。  

![image](/GIF/Desktop備份在自己電腦.gif)  

請叫出Desktop備份小精靈，依以下圖示步驟在你電腦產生相同內容的資料匣。 

2. 打開你電腦上的Github Desktop（假設你已經裝好了，如果還沒裝請連到這裡）。依以下步驟把範例repo下載回自己電腦。

3. 縮小Github Desktop，並切換到你範例repo在電腦上所存檔的資料匣（圖面範例是/github/Minicourse-Github-Desktop/)，在這裡專心做自己的事，下面畫面裡我做了兩作事：  
    - 修改目錄裡的README.md  
    - 新增一個檔案
  
4. 叫回Github Desktop，依範例Commit記錄上個步驟做的事，然後按Sync上傳到你的Github帳號。  


######    如果你想通知源頭repo擁有者你的更新：  

5. 在Github Desktop，按New Pull Request. 

