# Github基本介紹

### 什麼是Github.com？什麼是Github Desktop? 

這裡我們用非程式設計者懂的說法來解釋，故不符合它們原始的完整定義。  
- Github.com: 一個【雲端空間】讓你儲存備份用 

- Github Desktop: 安裝在你電腦上的【備份小精靈】，透過他，你可以選擇將某個資料匣裡的東西備份在自己電腦，或進一步備份在Github.com雲端空間。

我們先假設你已經在Github.com（以下簡稱.com）註冊了一個帳號，也在你電腦安裝了[Github Desktop](https://desktop.github.com/)（以下簡稱Desktop），並把Desktop設定好可以和你的.com帳號連結。 

### Github的使用狀況  

Github除了個人使用外，它也是團隊協作的利器，其中團隊協作又分成，為協作者（Collaborator）與不為協作者。協作者表示，你可以直接在.com的資料匣擁有者的頁面裡直接做某些修改，通常是認識的人才會採這種協作方式。然而，不是協作者依然可以協作，這就是所謂的開源（Open Source）協作。

開源協作表示某個人把自己的程式資料匣公開在.com，任何人都歡迎下載回去用，當然你在使用過程中有可能發現對方的bug，這時在Github裡還是有其他協作方式可進行。


我們依同一個.com資料匣（稱作repo）的使用人數及協作狀態，分成以下三種情況：



人數\是否為協作者 |不是 | 是 |
---|---|--|
單獨個人 | 【A】 | NA |
團隊 | 【B】 | 【C】 |

其中【A】表示你是獨立開發者，只是用Github來備份和記錄進程。【B】表示你下載了別人的repo，但有參與修正程式的可能。【C】表示你和別人分享同一個repo，一起協作開發。

### 角色： 主人【Master】

在我們繼續前，我們有必要記住一個角色，那就是repo的源頭擁有者，稱為主人【Master】。

在【A】狀況下，個人一定有主人角色；【C】可能是，可能不是，通常團隊的隊長才會是主人；【B】一定不是，因為你是下載別人的repo。

### Github使用需知   

>!!!注意!!!  
Github原本是設計來分享程式碼的，所以檔案都不會太大，請勿用Github來存大檔案，如影像、照片等。  

***
# Github使用狀況：【A】與【B】

【A】個人使用  
 
    自己是主人（Master），單純要備份及記錄進程用。  

【B】非協作者的團隊使用，稱為開源協作。  

    複製別人的資料匣來用，不是主人，但願意協助原開發者改善程式。  
    
以下步驟【壹】－【肆】是【A】、【B】兩種狀況都適用； 但步驟【伍】原則上只有【B】才會用到。

### 【壹】 在Github.com產生一個資料匣（New or Fork）  

- 狀況【A】：你會「先」在.com開好未來電腦所要備份的資料匣（稱為repo）名稱（此時你電腦還沒有那資料匣），「之後」才透過Desktop來幫你在電腦上開對應的資料匣。   

- 狀況【B】：你在.com看到別人公開的資料匣，想複製一份到自己的帳號裡－－這裡的複製動作稱為「**Fork**」。

###### 【練習一】複製別人的資料匣  
> 請連去tpemartin使用者的[「Minicourse-Github-Desktop」](https://github.com/tpemartin/Minicourse-Github-Destkop) repo, 然後點`Fork`把該資料匣完全複製到你的帳號裡。  

### 【貳】 在自己電腦產生對應.com某個repo的資料匣 （Clone） 

當你完成【練習一】後，我們接下來可以在你電腦裡產生同樣內容的資料匣－－這個動作叫複製下載【Clone】。  

- 請叫出Desktop備份小精靈，依以下圖示步驟在你電腦產生相同內容的資料匣。 

![image](/GIF/Desktop複製com資料匣.gif)

- 當你依照上面步驟進行後，你的電腦應該有一個名叫Minicourse-Github-Desktop的資料匣。 

### 【參】 備份電腦上的資料匣在自己電腦上 （Commit） 

這個動作叫備份承諾【Commit】。

乍聽之下這是件很奇怪的事，即然資料匣已經在自己電腦上，那還需要備份在自己電腦上嗎？  

這是個合理的問題。的確，如果你的硬碟壞了，備份當然也沒了。然而，Github的備份其實不只是備份，他會留下一個歷史版本，之後你如果繼續修改資料匣內的內容，那一天想回到上個月備份的資料匣內容，你還是可以透過備份小精靈【坐時光機】回去那個時點，這也是它為什麼叫承諾－－因為說過／做過的事都會被清楚記下來。

- 請在你電腦裡的Minicourse-Github-Desktop資料匣，做任何內容變更，如修改裡面的檔案，或加、刪一個檔案，接著依照以下的步驟進行備份（在下面的步驟，我已經在該資料匣新增了一個data-wrangling-cheatsheet.pdf檔，當然你做的變動會和這裡不一樣）。  

![image](/GIF/Desktop備份在自己電腦.gif)  

請叫出Desktop備份小精靈，依以下圖示步驟在你電腦產生相同內容的資料匣。 

### 【肆】 備份電腦上的資料匣到自己的.com帳號裡 （Sync）

這個動作叫++同步備份++【Sync】，因為備份到雲端也是同步到雲端的意思。

- 請依圖示備份你電腦上的Minicourse-Github-Desktop資料匣到你的雲端空間。  

![image](/GIF/Desktop備份到com雲端.gif)  

### 【伍】 請求複製資料匣的源頭接受你的合併更新請求（Pull Request）   

主要只適用在狀況【B】－－開源協作狀態。  

當你使用源頭使用者（如這裡的tpemartin）的資料匣內容時，你可能幫他改善了些檔案，或新增了些檔案，使他的repo內容更完美。你除了會同步備份到自己的.com雲端空間，還可能會希望源頭合作者也接受你的更新，這時要做的動作叫++送出合併更新請求++【Pull Request】。  

- 當你備份完你電腦上的Minicourse-Github-Desktop資料匣到你的雲端空間後，請依以下圖示送出Pull Request給tpemartin，請他接受你的合併請求。  

![image](/GIF/Desktop送出Pull_Request.gif)

###### 【練習二】  
> 請在你電腦上的Minicourse-Github-Desktop資料匣打開一個名為`Practice.md`的文字檔，在裡面寫些字，存檔後送出Pull Request給tpemartin進行合併更新，我收到後會䀆快進行合併動作，之後你連到[https://github.com/tpemartin/Minicourse-Github-Destkop](https://github.com/tpemartin/Minicourse-Github-Destkop) 點開網頁上的`Practice.md`檔應該會看到你留的文字。
