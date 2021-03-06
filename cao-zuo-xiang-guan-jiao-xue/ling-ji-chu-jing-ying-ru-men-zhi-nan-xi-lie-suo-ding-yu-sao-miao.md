# 鎖定與掃描

## 精英危险中文论坛

## 【零基础精英入门指南系列】鎖定與掃描

#### 作者: y1n4

> 此教學不會提及FSS以及DSS訊號分析內容，相關教學請前往[此處](https://forum.elitedanger.cn/d/136-beyond)查看

本教學內容：

1. 鎖定目標
   * 鎖定子系統
2. 鎖定掃描
   * 掃描載具
3. 掃描信標
4. 數據連接掃描
5. 短距成分掃描
6. 擊殺委任掃描
7. 貨艙掃描
8. 空間摺叠訊號掃描

使用按鍵：

* T：鎖定前方目標
* Y：循環鎖定目標的子系統（即部件）

（明天才補圖）

#### 作者: y1n4

## 鎖定目標

ED裡駕駛載具時，只要對著前方，在物件出現**白色細線框框**時點擊【T】鍵（SRV默認為滑鼠【右鍵】，建議更換），就會鎖定該目標，在畫面上也會出現該目標的名稱和距離。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618319181-898127-aftertargetdes.jpeg)

而在一般空間裡，雷達上鎖定的目標圖示**會出現&lt;&gt;符號**。左下角的目標面板也會顯示該目標的資訊。

如果鎖定的目標是星體、太空站、訊號、躍遷目的地星系之類的，那麼**雷達左上角還會顯示『訊號羅盤』**，告知你該訊號相對你的位置：若羅盤中**白點是實心**的，代表此目標或**訊號就在我們前方**；如果中是**空心白圈**，則代表**目標訊號在我們後方**。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618319557-26514-signaltargetatdes.jpeg)

### 鎖定子系統

除了鎖定整個目標，鎖定目標後，點擊按鍵【Y】也能在對方的不同子系統（一般而言是部件）之間循環鎖定，並以紅色框顯示，左下角的目標面板也會顯示該子系統的血量。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618319734-537728-targetsubsystem.jpeg)

這在戰鬥中很有幫助，可以讓你的武器特別鎖定指定部件位置瞄準進行攻擊

若覺得點擊【Y】鍵一個個循環很麻煩，也可以在鎖定目標後，於1號面板切換至最右邊的【Target】分頁，在【Sub-Targets】分頁直接選擇要鎖定的子系統。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618319868-474210-targetsubsystem02.jpeg)

#### 作者: y1n4

## 鎖定掃描

鎖定掃描是ED裡最基礎的掃描方式，在載具（如飛船上）中默認**對前方目標按【T】鍵鎖定**後，將載具**面向該目標**，只要**在一定距離內和角度範圍內**，就會聽見開始掃描的提示音，完成後畫面上以及右上資訊界面也會提示掃描完畢。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618319181-898127-aftertargetdes.jpeg)

### 掃描載具

不管是超巡中還是一般空間，我們也能使用此方式掃描所遇見的飛船或載具，進而得知對方的載具名字、駕駛員名字、所屬團體，於**當前管轄區**內是否有懸賞等。掃描時左下的目標面板會有轉動圖示。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-14/1618404540-328102-killwarrant02.jpeg)

若有懸賞，在1號面板的【Contact】分頁也也會顯示該目標的懸賞金額。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-14/1618404445-916466-killwarrant01.jpeg)

掃描偶爾會隨機得到數據材料。

#### 作者: y1n4

## 掃描信標

掃描信標（Beacon，導航信標或觀光信標方式一樣）的方式其實和掃描飛船類似，但**只能在一般空間**內進行。

在超巡接近信標訊號區域並脫離進入一般空間後，我們會在畫面上看到橘色的圈寫著【Nav Beacon】

然而這其實**不是信標的實體位置**，而單純只是說明這個訊號空間是『信標區域』而已。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618320163-91049-beaconscan01.jpeg)

而新手最常犯的錯就是**誤把橘色圈的訊號區域當作信標實體位置**，所以怎麼掃都沒反應。

實際上信標在雷達上會是白色的框框，基本上在雷達上理應不會漏掉。如果真的太多東西找不到，就打開1號面板去到【Contact】分頁，找到【Nav Beacon】之後用【空格】鍵鎖定

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618320255-546267-beaconscan02.jpeg)

回到駕駛界面，留意雷達上有&lt;&gt;符號的白色點點，那就是信標了，向著它並接近，就會聽見開始掃描的聲音，並聽到完成掃描的提示。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-13/1618320383-327127-beaconscan03.jpeg)

> 新手開局教學流程中用數據連接掃描儀的是**特殊方式**，一般不用這樣。

#### 作者: y1n4

## 數據連接掃描

此掃描方式會使用數據連接掃描儀（Data Link Scanner），這是所有飛船自帶的內建部件。

需在4號面板的【Firegroup】分頁設定按鍵方可使用。

一般來說用來掃描太空據點（Installation）的數據點（Data Point）、地面據點（Settlement）的數據點、掃描取得Guardian遺跡的藍圖、分析巨型飛船（Megaship）的子系統好鎖定進行後續作業等。

![2019-04-03 23-02-51.mp4\_20190421\_085047.707.jpg](https://cdn.elitedanger.cn/Fl44RZlE7VijcHXEd4um8tHvOUf7.jpg)

![2019-04-03 23-02-51.mp4\_20190421\_085523.048.jpg](https://cdn.elitedanger.cn/FvLZbBN0cQyL7S4datEm6gRUxTSt.jpg)

一樣鎖定、面對並接近目標後（需要滿靠近的，某些東西甚至要350m以內，如上圖），切換到特定的開火組（Firegroup）並且為**分析模式**（Analysis Mode）後，對著目標**按著使用建**，等進度完成即可。

![0\_1537687482414\_guide2211.jpg](https://cdn.elitedanger.cn/Fv8u6hLQTKaMNq2pxcLvOlx0Ls6f)

> 新手強制開局教學流程就是用此方式掃描信標，一般不用這樣。

#### 作者: y1n4

## 短距成分掃描

這東西需要用短距成分掃描（Short Range Composition Scanner）來進行，一般是用來掃描奇特地質或者生物體用的，屬於探索用部件，也是飛船自帶。

一樣要在4號面板的【Firegroup】開火組設定使用按鍵。

之後只要在看到奇特物質時，切換為分析模式【Analysis Mode】，對準目標在一定距離內（瞄準可掃描物體時準星會高亮），按著設定鍵就會進行掃描。

![https://cdn.elitedanger.cn/FvKjsWb50t-xcpm1WN\_4YoTJ9W3i.jpg](https://cdn.elitedanger.cn/FvKjsWb50t-xcpm1WN_4YoTJ9W3i.jpg)

#### 作者: y1n4

## 擊殺委任掃描

擊殺委任掃描儀（Kill Warrant Scanner）是用來掃描目標飛船，找出該飛船是否在當前管轄區外有通緝懸賞的儀器。

此部件需要在功能部件槽（Utility Mount）上購買並安裝，且一樣要在4號面板的開火組【Firegroup】設定按鍵使用。

但此部件能在戰鬥模式【Battle Mode】下使用。

一般而言可增加目標的懸賞金額。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-14/1618404850-644667-killwarrant03.jpeg)

> 注意：
>
> 即便經過掃描，目標飛船在其他管轄區有賞金，**但若對方在當前星系是清白狀態**，對他發動攻擊或將之擊毀**也會導致你被通緝**。

## 貨艙掃描

貨艙掃描儀（Manifest Scanner）可以用來掃描目標飛船的貨艙，得知對方所攜帶的貨物。此部件需要在功能部件槽（Utility Mount）上購買並安裝，且一樣要在4號面板的開火組【Firegroup】設定按鍵使用。

完成掃描後，就可以在鎖定目標後，在1號面板的最右邊【Target】分頁，下面的【Manifest】子分頁查看目標攜帶的貨物。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-14/1618404956-385247-manifest01.jpeg)

#### 作者: y1n4

## 空間摺叠訊號掃描

空間摺叠訊號掃描儀器（Frame Shift Wake Scanner）主要用來掃描一般空間裡其他飛船躍遷之後留下的高能量空間摺叠訊號（一般被叫做『尾氣』），掃描完畢後可以得知對方躍遷目的地，也能鎖定該訊號進行躍遷跟隨。

此外，如此掃描也會隨機得到[數據材料](https://forum.elitedanger.cn/d/111-horizon)。

此部件需要購買並安裝在功能部件槽（Utility Mount）上，一樣要在4號面板的開火組【Firegroup】設定按鍵使用。

在某些刺殺或者剿匪任務會用到。

