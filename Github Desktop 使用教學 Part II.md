


### 【壹】 下載共同協作repo

直接進入[Part I的步驟【貳】clone](https://github.com/tpemartin/Minicourse-Github-Destkop/blob/master/Github%20Desktop%20%E4%BD%BF%E7%94%A8%E6%95%99%E5%AD%B8%20Part%20I.md#貳-在自己電腦產生對應com某個repo的資料匣-clone)，有時你會看到不屬於自己.com帳號下的repo，如下面紅色圈起來的地方。它表示有個叫jihc8251的使用者，他是lala這個資料匣（repo）的主人（Master），但他把我加入成為共同協作者（Collaborator），所以我什麼都不做，它也會出現在我的clone清單裡。這時，你可以直接依照之前的步驟【貳】，下載複製那個資料匣在你的電腦裡。

![image](/GIF/Different_clone_types.png)

當然，你沒辦法下載圖片裡的repo，因為你並不是共同協作者且那個repo是私人的。 


我們回到使用之前的Minicourse-Github-Desktop資料匣為例，繼續本次的課程介紹，我假設你已經有請老師把你加到Minicourse-Github-Desktop成為Collaborator。如果是的話，而你上次也已經fork了那個資料匣，那你在這階段應該會有兩個如下的同名repo：一個有叉子圖案，是fork回自己.com帳號的；另一個有主人使用者名稱，是對方邀你協作的。（你應該有兩個Minicourse-Github-Desktop）

![image](/GIF/fork_vs_collaborate.png)  

我們今天要選擇沒有叉子的，也就是`tpemartin/Minicourse-Github-Desktop`，並請你將它clone回來你電腦。

### 【貳】創造協作身份（Branch）  

步驟【壹】只有clone該repo到你電腦，而在.com雲端你和源頭主人（這裡的tpemartin）其實是共用同一個repo資料匣，如果你們都各自直接對此雲端repo修改，那打架的機會很高，所以協作者應該在自己電腦上先創造一個協作分身，另外取名以和Master有所區分，這個動作叫創造協作身份 【Branch】。

請依圖示用Desktop在你的電腦創造一個Branch： 

![image](/GIF/Desktop創造Branch.gif)  

這裡你可以注意到Desktop的右上角多了一個支節，且藍色大圓點是在新分出來的支節上，這表示你現在在你電腦上的Minicourse-Github-Desktop所做的任何事，都會記錄在這個`My-own-branch`支節上，而不會記在上面的那個`Master`支節裡。

### 【參】備份電腦上的資料匣在自己電腦上 （Commit） 

假設你做了一些事，之後你還是跟以前一樣會先在自己電腦上做備份承諾【Commit】。

請開啟你電腦Minicourse-Github-Desktop資料匣裡的`Practice.md`檔，隨便加些字，存檔。接著，依圖示用Desktop在你的電腦做備份承諾：

![image](/GIF/Desktop_commit_to_my_branch.gif)

你會注意到這新的Commit是在你的分支上。

### 【肆】 備份電腦上的commit到自己的.com帳號裡 （Publish or Sync）

請依圖示進行雲端備份，由於是開分支之後第一次雲端備份，它會在雲端也新開一個同樣名稱的分支，才把你的Commit備份上去，由於是「第一次」做雲端分支備份，所以叫【Publish】。

![image](/GIF/Desktop開佈新branch.gif)

另外，有沒有注意到上圖Publish完後，同一個按鍵名稱又變成【Sync】，表示下次你在Desktop有新Commit又要備份到雲端已存在的分支時，它就會叫【Sync】—— 和以前Part I相同名稱。

### 【伍】 請求雲端共同協作的主人Master接受你分支的合併更新請求（Pull Request）

當你在分支Commit-Sync一陣子之後，你對你的修改滿意了，這時你會希望Master把你的修改也收回到Master主支節上，這個動作跟以前一樣叫【Pull Request】。

這裡我們先依圖示，在Desktop的repo裡按滑鼠右鍵選`View on Github`把雲端的repo網頁叫出來。  

![image](/GIF/Desktop_view_on_Github.gif)

接著依圖示進行併入Master的合併請求：  

![image](/GIF/雲端送出分支Pull_request.gif)


