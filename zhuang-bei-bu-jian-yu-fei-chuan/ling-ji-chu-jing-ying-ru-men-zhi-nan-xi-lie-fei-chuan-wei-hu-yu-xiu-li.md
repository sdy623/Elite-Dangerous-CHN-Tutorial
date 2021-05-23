# 飛船維護與修理

## 精英危险中文论坛

## 【零基础精英入门指南系列】飛船維護與修理

#### 作者: y1n4

本教學會說明飛船的修理事項：

1. 站點內修理
   * 船體耐久度
   * 船體折舊度
   * 部件耐久度
2. AFMU 部件維修套組
3. 船體維修無人機
4. 重啟/維修
5. SRV維修
6. 玩家協助維修裝甲服務：Hull Seal

#### 作者: y1n4

## 站點內修理

飛船有好幾個會受損的項目：

* 船體耐久度 hull
* 船體折舊度 hull integrity
* 部件耐久度 module integrity

### 船體耐久度 hull

船體耐久度hull，最直觀的項目，主駕駛頁面下面就會顯示%數，**0%就炸船**了。

![](https://qiniu.elitedanger.cn/assets/files/2021-04-18/1618761516-91836-weaponspeacialeffecticon.png)

可以在停機坪的快速維修來修理

![](https://qiniu.elitedanger.cn/assets/files/2021-04-16/1618580147-747641-landingpadpanelody01.jpeg)

#### 地平線界面

也可以在站點服務頁面的右下角點快速維護，或者點開進階維護來修理（地平線）

![](https://qiniu.elitedanger.cn/assets/files/2021-01-02/1609559690-887911-stationmenu02.png)

點擊上面左邊即可修理全部（飛船塗裝噴漆paintwork默認不會一起修理）

![](https://qiniu.elitedanger.cn/assets/files/2021-04-19/1618853007-70670-advancedmaintenance01.jpeg)

#### 奧德賽界面

點擊右下角的高級維護

![](https://qiniu.elitedanger.cn/assets/files/2021-04-16/1618578014-690033-stationpanelody01.jpeg)

之後點擊修理

![](https://qiniu.elitedanger.cn/assets/files/2021-04-16/1618602801-836809-stationpaneladvmaint01.jpeg)

### 船體折舊度 hull integrity

船體折舊度integrity是一個隱藏的數值，在飛船上沒辦法查看，只能在站點的進階維護才能知道剩下多少。

這個數值會因為你飛船駕駛久了，或者超巡久了而急速下降。這個數值如果降到0%，**船體耐久度hull的最大值也會只剩70%**（但對飛船來說是滿的，所以無傷害狀態下船體耐久度hull還是會顯示為100%），**據說**這個值越低，也**容易被武器打穿傷害內部部件**（見下面項目）

一般來說只要在站點的進階維修處多修修就不會有問題。

在進階維護頁面，點擊上面右邊即可修理（價格略高，且費用非線性）

![](https://qiniu.elitedanger.cn/assets/files/2021-04-19/1618853007-70670-advancedmaintenance01.jpeg)

### 部件耐久度 module integrity

飛船的內部部件、外部武器掛點、外部功能部件也都有自己的耐久度（血量）。戰鬥中如果**打中外部部件**，或者**特定船體位置被打穿並擊中該位置內部的部件**，該部件就會受損（此時不會扣除船體耐久度hull的血量）

**部件耐久度降低到一定%數，部件就會隨機失效**。

如果**飛船發電機**（Powerplant）被打壞，其**發電率就會變為40%**，如果再持續被擊中，就**有一定機率導致直接爆船**，無視飛船的剩餘船體耐久度hull。

飛船上可以藉由4號面板的【Module】分頁查看部件的耐久度。

![](https://qiniu.elitedanger.cn/assets/files/2021-01-02/1609562477-962612-internalpanelmodule01.png)

一般來說只要在停機坪點擊快速維護，或者在進階維護頁面修理全部也會一同修理完畢

#### 奧德賽界面

點擊右下角的高級維護後，內部維護就可以選擇特定的部件維修或者全部維修

![](https://qiniu.elitedanger.cn/assets/files/2021-04-16/1618602801-836809-stationpaneladvmaint01.jpeg)

#### 作者: y1n4

## AFMU 部件維修套組

AFMU全稱『Auto Field Maintenance Unit』，為可選內部部件（Optional Internal）之一，商店名稱為『AFMS』（我也不知道那個S啥意思）

部件的主要規格，可維修的總部件血量為：『維修耗材』×『維修率』

![](https://qiniu.elitedanger.cn/assets/files/2021-04-19/1618853616-538277-afmu01.jpeg)

安裝並確定通電後，此部件可維修飛船的部件與武器。

開啟4號面板並切換至【Module】部件分頁，空格選定要維修的部件之後選擇右邊的【Repair】

此時部件會被關閉並緩慢進行維修，會有特殊的音效以及扳手符號

![](https://qiniu.elitedanger.cn/assets/files/2021-04-20/1618922199-450593-afmu02.jpeg)

> 由於維修時會關閉部件，因此AFMU有兩個**無法維修的東西**，即**自己以及發電機Power Plant**。
>
> 但藉由兩台AFMU就可以互相修理。

注意：

* 維修Thruster推進器以及FSD空間折疊引擎時必須在一般空間內。
* **船體耐久度hull無法使用AFMU修理**，請參考下面的**船體維修無人機**。
* 維修耗材用光之後需要在站點的補充界面買入，或者合成。
* 維修後部件會保持關閉狀態，記得手動開啟。

#### 作者: y1n4

## 船體維修無人機

船體維修無人機（控制器）Repair Limpet（Controller）為可選內部部件（Optional Internal）之一

可以用來維修飛船的船體耐久度（hull）

![](https://qiniu.elitedanger.cn/assets/files/2021-04-19/1618853730-648019-repairlimpet01.jpeg)

> 記得買入無人機
>
> 安裝並確定通電後，一樣在【Fire Group】設置部署的按鍵
>
> 接著在一般空間內，在未鎖定飛船的情況下釋放無人機，就會維修自身飛船船體了。
>
> ![](https://qiniu.elitedanger.cn/assets/files/2021-04-20/1618922464-108462-repairlimpet02.jpeg)

完成後無人機就會自行脫離。

此無人機在鎖定其他飛船的情況下也可以維修其他飛船的船體耐久度hull。

#### 作者: y1n4

## 重啟/維修

如果剛好在外，一些關鍵部件壞得只剩下0%了怎麼辦。

這時你可以~~自爆~~用飛船的重啟維修功能

此功能是藉由重啟，調用其他血量在5%以上的部件來維修你血量已變為0%的部件。

在4號面板，【Ship】分頁的【Functions】子分頁，找到【Reboot/Repair】

![](https://qiniu.elitedanger.cn/assets/files/2021-04-20/1618923397-430552-rebootrepair01.jpeg)

點擊後會需要再等3秒才能點擊【Confirm】確認維修

![](https://qiniu.elitedanger.cn/assets/files/2021-04-20/1618923445-712218-rebootrepair02.jpeg)

## SRV維修

SRV的耐久度會在回到飛船後自動維修。

也可以藉由4號面板的【SRV】分頁，最底下的【Synthesis】分頁來維修SRV【SRV Repair】（需消耗材料）

> 但燃料就要飛船回到站點停靠才會補充。

#### 作者: y1n4

## Hull Seal

直譯『裝甲海豹』，是類似[Fuel Rat](https://forum.elitedanger.cn/d/734/5)玩家組織。

官網在此：[這裡](https://hullseals.space/)

可以呼叫來替你維修船身耐久度。

