# 部件說明

## 精英危险中文论坛

## 【零基础精英入门指南系列】部件說明

#### 作者: y1n4

此內容會說明飛船部件分類、級別、評級、以及各部件的功能

1. 部件種類
2. 級別與評級
3. 部件規格
4. 核心部件
   * Bulkhead 飛船裝甲
   * Power Plant 反應爐（發電機）
   * Frame Shift Drive 空間折疊引擎
   * Thruster 推進器
   * Sensor 探測儀
   * Life Support 維生系統
   * Power Distributor 電力分配器
   * Fuel Tank 油箱
5. 可選部件
   * 工具類
   * 防護類
   * 裝載類
   * 掃描儀類
   * 載具倉庫類
   * 無人機控制器類
6. 功能部件
   * 防禦類
   * 掃描儀類
7. 掛架裝備（武器）
   * 分類說明：尺寸、瞄準模式、傷害類型
   * 熱能武器
   * 動能武器
   * 熱能動能混合武器
   * 爆破型武器
   * AX武器
   * 挖礦工具
8. 內建部件

#### 作者: y1n4

## 部件種類

飛船的部件根據內外和必要性分為：

* 核心內部部件
* 可選內部部件
* 功能外部部件
* 外部掛架裝備
* 內建部件

### 核心內部部件 Core Internal

即飛船不可或缺的部件類型。

又可細分為：

* Bulkhead 飛船裝甲
* Power Plant 反應爐（發電機）
* Frame Shift Drive 空間折疊引擎
* Thruster 推進器
* Sensor 探測儀
* Life Support 維生系統
* Power Distributor 電力分配器
* Fuel Tank 油箱

### 可選內部部件 Optional Internal

可選擇安裝於飛船的額外部件，並非必備，主要是拓展飛船的功能，也是ED裡最多變的大項目之一。

此部件種類繁多，根據你的進行事項選擇安裝即可。

### 功能外部部件 Utility

這類部件大多是一些輔助掃描儀或者安裝於飛船外部的輔助部件。

### 外部掛架裝備 Hardpoint Equipment

一般來說就是武器以及一些挖礦設備。

### 內建部件 Integrated

這類部件是一些內建的掃描儀，或者貨艙口。

## 級別與評級

飛船的各個部件又根據大小和好壞分為『級別』（Class）和『評級』（Rating）

級別一般都用數字表示；而評級則用字母表示。

比如2A推進器，即尺寸為2的A級推進器。

一般來說，飛船尺寸越大，默認安裝的部件級別就會越大。

而飛船購買時的部件一般都是E級，也就是最低級的部件。

除了武器裝備（Hardpoint）和功能部件（Utility）之外

其他部件大致上都可以分為：

* E級：最爛最便宜
* D級：功能差，特點是**重量最輕**
* C級：性價比平均
* B級：**重量最重**，部件**耐久度（血量）最高**
* A級：**效能最好**，重量比D級稍重，他媽**爆貴**

## 部件規格

* Class（級別）：即部件的尺寸大小。
* Rating（評級）：部件的性能。
* Mass（質量）：即重量，會影響飛船的機動性，遷躍能力。
* Integrity（耐久度/完整度）：此數值越高，越能承受更多穿透船身擊中該部件的攻擊。
* Power Draw（耗電）：該部件的用電量。
* Value（價格）：部件的買入價。

#### 作者: y1n4

## 核心部件 Core Internal

核心部件（Core Internal）為飛船的主要內部部件，也是飛船的核心組成。

這類部件在拆除後，都須要找其他的換上；

若無，則系統會自動為飛船安裝最低評級（Rating）的默認等級（Class）部件。

### 飛船裝甲 Bulkhead

為飛船船身提供防護，即裝甲耐久度（hull point），簡單來說就是飛船的血量，為0%時就會爆船。

越重的裝甲也提供越多的裝甲耐久度，但相應的價格高、重量重。

飛船裝甲有五種可安裝：

* 原廠輕量合金裝甲（Lightweight Alloy）：為飛船買來時自帶的版本，也是重量最輕，裝甲量最低的
* 強化合金裝甲（Reinforced Alloy）：這類裝甲可以提供更多裝甲耐久度，而且有較好的碰撞抗性
* 軍用裝甲（Military Grade Composite）：此裝甲提供最頂級的裝甲耐久度，也有最高的碰撞抗性
* 鏡面裝甲（Mirrored Surface Composite）：這款裝甲的耐久度和軍用裝甲一樣，有更好的熱能（雷射）傷害抗性，但動能（實彈）傷害抗性較低，也有最高的碰撞抗性
* 反應裝甲（Reactive Surface Composite）：這款裝甲的耐久度和軍用裝甲一樣，有較好的動能（實彈）傷害抗性，但熱能（雷射）傷害抗性較低，也有最高的碰撞抗性

規格：

* Mass：質量
* Hull Boost：耐久度增加量
* Kinetic Resistant：動能傷害抗性（若為負值，代表受到此類攻擊會有增傷效果）
* Thermal Resistant：熱能傷害抗性（若為負值，代表受到此類攻擊會有增傷效果）
* Explosive Resistant：爆破傷害抗性（若為負值，代表受到此類攻擊會有增傷效果）

### 反應爐（發電機）Power Plant

簡稱PP，消耗[燃料](https://forum.elitedanger.cn/d/734)為全船供電。等級越大、評級越高，發電量越多，產生的廢熱也越少。

如果發電機被攻擊，部件耐久度（血量）剩下0%，其發電效率就會只有40%，如果這時再被攻擊發電機，每次被擊中就有一定機率直接導致飛船殉爆（無視剩餘的裝甲耐久度）。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Capacity：發電量
* Heat Efficiency：發熱效率（數字約低越好）

### 空間折疊引擎 Frame Shift Drive

簡稱FSD，讓飛船可以進行[超級巡航](https://forum.elitedanger.cn/d/739)以及[超空間躍遷](https://forum.elitedanger.cn/d/740)。等級和評級對超巡幾乎毫無影響，但會極大影響躍遷的距離。

越大越好的FSD會有越多的燃料使用上限以及較高的最適運作重量，因此在船重固定不變的情況下，越大越好的FSD就能跳越遠。

使用中子星或白矮星超級充能可以提升FSD的單次躍遷距離，但躍遷後會降低[部件耐久度](https://forum.elitedanger.cn/d/744)1%。

耐久度低於一定%數，FSD就會隨機失效，導致超巡時緊急離開超巡，或者躍遷超巡充能失敗等。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Draw：耗電
* Boot Time：關機開啟時間（並非充能時間）
* Optimised Mass：最適運作質量，飛船的總重為此重量時FSD的使用效率最好
* Thermal Load：廢熱
* Max Fuel Per Jump：躍遷燃料使用上限

### 推進器 Thruster

簡稱推子，讓飛船可以在一般空間進行機動，會影響飛船的速度、極速、後燃器極速、翻滾速度、俯仰速度、偏好速度等。簡言之，推進器越好，飛船約靈活。

有款特殊的型號為【增強型推進器】（Enhanced Performance Thruster），只提供小型飛船安裝，且只有部分站點販賣。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Draw：耗電
* Optimal Mass：最適運作質量，飛船的總重為此重量時推進器的使用效率最好
* Maximum Mass：最大運作質量，飛船的總重超過此重量時推進器就無法使用
* Thermal Load：廢熱

### 探測儀 Sensor

決定了飛船的[掃描儀](https://forum.elitedanger.cn/d/742)上會顯示多遠的目標。若損壞或關閉的話會影響鎖定，且輔助瞄準（Gimbal）與砲塔（Turret）武器也無法使用。 損壞時也無法向站點[申請停靠](https://forum.elitedanger.cn/d/741)。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Draw：耗電
* Boot Time：關機開啟時間
* Max Range：探測範圍
* Target Scan Angle：目標掃描角度
* Typical Emission Range：平均散發偵測範圍，一般溫度飛船在此距離以內就會顯示於雷達上

### 維生系統 Life Support

用來維持飛船內的可呼吸環境，並在駕駛艙艙蓋破裂後提供緊急氧氣，級別越高可供氧越久。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Draw：耗電
* Boot Time：關機開啟時間
* Emergency Life Support：緊急氧氣儲備時間

### 電力分配器 Power Distributor

能將發電機產生的電分配至系統、推進器，與武器的[電容](https://forum.elitedanger.cn/d/750-pips)。越好的分配器便能更快補充不同電容內的電量。

規格：

* Mass：質量
* Integrity：部件耐久度
* Power Draw：耗電
* Boot Time：關機開啟時間
* Weapon Capacity：WEP電容量
* Weapon Recharge：WEP電容充電率
* Engine Capacity：ENG電容量
* Engine Recharge：ENG電容充電率
* System Capacity：SYS電容量
* System Recharge：SYS電容充電率

### 油箱 Fuel Tank

即裝填燃料用的容器，決定你最多能裝多少燃料，本身無重量，根據裝入的燃料而變更重量。

規格：

* Fuel Capacity：燃料容量

#### 作者: y1n4

## 可選內部部件

![](https://qiniu.elitedanger.cn/assets/files/2021-04-25/1619325220-844353-all-optional-module-01.png)

根據用途可大致分為以下種類：

### 工具類

* 部件維修套組（Auto Field-Maintenance Unit）：用來[維修](https://forum.elitedanger.cn/d/744)自己飛船的部件，無法幫其他飛船維修，會消耗專用耗材，可在【Advanced Maintenance】補充
* FSD攔截器（Frame Shift Drive Interdictor）：將其他飛船[從超巡中拉出](https://forum.elitedanger.cn/d/748)。
* 油勺（Fuel Scoop）：用來從特定恆星種類[提取燃料](https://forum.elitedanger.cn/d/734)
* 精煉機（Refinery）：將拾取的礦物碎片精煉為可販賣的礦物商品
* 標準停靠電腦（Standard Docking Computer）：可進行[自動停靠](https://forum.elitedanger.cn/d/741)
* 加強型停靠電腦（Advanced Docking Computer）：可進行[自動停靠與起飛](https://forum.elitedanger.cn/d/741)
* 守護者遷躍距離增幅儀（Guardian Frame Shift Drive Booster）：可直接[增加飛船躍遷距離](https://forum.elitedanger.cn/d/740)
* 超巡輔助（Supercruise Assist）：為飛船提供[超巡鎖定輔助與自動脫離](https://forum.elitedanger.cn/d/739)、躍遷後[自動降低油門](https://forum.elitedanger.cn/d/740)等功能

### 防護類

* 能量護盾生成器（Shield Generator）：為飛船生成保護屏障，抵擋外來攻擊
  * 雙編能量護盾生成器（Bi-Weave Shield Generator）：盾量較小，但破盾後恢復較快，只有C級
  * 棱鏡能量護盾生成器（Prismatic Shield Generator）：[帝國公主Aisling Duval](https://forum.elitedanger.cn/d/89-powerplay)的[勢力部件](https://forum.elitedanger.cn/d/331)，盾量大
* 能量護盾電池（Shield Cell Bank）：在破盾前使用可直接回复一定的能量護盾耐久度，使用時飛船會產生高熱，破盾後無法使用
* 船體加固套組（Hull Reinforcement Package）：可增加飛船的裝甲耐久度
* 部件加固套組（Module Reinforcement Package）：攻擊擊穿飛船裝甲時，會代替部件優先承受傷害，完全消耗即失效
* 超合金船體加固套組（Meta Alloy Hull Reinforcement Package）：攻擊擊穿飛船裝甲時，會代替部件優先承受傷害，完全消耗即失效，特點在於有部分腐蝕抗性
* 守護者船體加固套組（Guardian Hull Reinforcement Package）：攻擊擊穿飛船裝甲時，會代替部件優先承受傷害，完全消耗即失效，特點在於有部分腐蝕抗性且增加了熱能傷害抗性
* 守護者能量護盾加固套組（Guardian Shield Reinforcement Package）：可增加飛船的能量護盾耐久度
* 守護者部件加固套組（Guardian Module Reinforcement Package）：攻擊擊穿飛船裝甲時，會代替部件優先承受傷害，完全消耗即失效，特點在於可以防止由Thargoid Interceptor閃電攻擊造成的HUD加擾和強制部件重啟效果

### 裝載類

* 貨物架（Cargo Rack）：裝載貨物罐、商品或物件用
  * 防腐蝕貨物架（Corrosion Resistant Cargo Rack）：裝載貨物罐、商品或物件用，有抗腐蝕能力
* 客艙（Passenger Cabin）：裝載乘客用，為客運任務必備部件，分為經濟艙（Economy）、商務艙（Business）、頭等艙（First）和豪華艙（Luxury）四個級別
* 油箱（Fuel Tank）：擴增的[燃料](https://forum.elitedanger.cn/d/734)容器

### 掃描儀類

* 星體表面掃描儀（Detailed Surface Scanner）：可對星體投放地表探測儀，完全探測後可知曉表面的POI位置

### 載具倉庫類

* 地面載具車庫（Planetary Vehicle Hangar）：裝載並部署地面載具SRV用
* 艦載機機庫（Fighter Hangar）：裝載並部署艦載機SLF用

### 無人機控制器類

無人機控制器（Limpet Controller）工程師可為無人機進行編程，以進行各種事項。需要同時安裝貨物架並購買無人機（Limpet）方可使用：

* 收集無人機（Collector Limpet Controller）：能於太空中[拾取物品](https://forum.elitedanger.cn/d/730)
* 汙染物清除無人機（Decontamination Limpet Controller）：用以清除飛船外部的腐蝕性物質
* 燃料傳輸無人機（Fuel Transfer Limpet Controller）：向目標飛船[傳輸燃料](https://forum.elitedanger.cn/d/734)
* 貨艙門破壞無人機（Hatch Breaker Limpet Controller）：破壞目標飛船的貨艙門
* 礦物探勘無人機（Prospector Limpet Controller）：射向小行星，可得知其礦物含量
* 駭入無人機（Recon Limpet Controller）：對數據點進行駭入，盜取資料
* 船體維修無人機（Repair Limpet Controller）：可維修自身或鎖定目標飛船的[裝甲耐久度](https://forum.elitedanger.cn/d/744)（hull）
* 樣本採集無人機（Research Limpet Controller）：可在有機體身上採集樣本

#### 作者: y1n4

## 功能外部部件

![](https://qiniu.elitedanger.cn/assets/files/2021-04-25/1619326857-261629-all-utility-module-01.png)

這類部件的尺寸一律為1，且重量都是1.3噸，也不區分評級。

### 防禦類

* 能量護盾增幅器（Shield Booster）：提升飛船的能量護盾耐久度
* 干擾箔條發射器（Chaff Launcher）：可短暫解除其他飛船對自己的鎖定，會影響對方的輔助瞄準（Gimbal）與自動砲塔（Turret）
* 點防禦砲塔（Point Defence）：可自動攻擊來襲的飛彈、火箭、魚雷、空雷
* 儲熱槽發射器（Heat Sink Launcher）：可降低飛船的溫度，消耗品
* 電子反制儀（Electronic Countermeasure，簡稱ECM）：能讓導彈和魚雷的鎖定失效，需在正確時機長按放開使用
* 電磁波中和力場生成器（Shutdown Field Neutraliser）：能讓EMP攻擊失效，需在正確時機長按放開使用

### 掃描儀類

* 空間摺叠訊號掃描儀（Frame Shift Wake Scanner）：在一般空間內使用，能得知從一般空間進入超空間的飛船之[躍遷目的地](https://forum.elitedanger.cn/d/728)並鎖定
* 貨倉掃描儀（Manifest Scanner）：在一般空間內使用，能得知目標飛船所[裝載的物品](https://forum.elitedanger.cn/d/728)
* 擊殺委任掃描儀（Kill Warrant Scanner）：在一般空間內使用，能得知目標飛船在[其他管轄區是否有懸賞](https://forum.elitedanger.cn/d/728)
* 脈衝礦物偵測儀（Pulse Wave Analyser）：在一般空間內使用，能得知小行星是否有核心礦物
* 外星載具掃描儀（AX Xeno Scanner）：在一般空間內使用，能得知目標Thargoid飛船的種類，並鎖定其子系統

#### 作者: y1n4

## 外部掛架裝備

### 分類說明

#### 尺寸級別

飛船武器根據尺寸分為S小（Small）、M中（Medium）、L大（Large）、H巨（Huge）。

較大的武器一般有較高的傷害、較大的穿甲數值。

#### 傷害類型

根據傷害類型分為熱能（雷射，Thermal）、動能（實彈。Kinetic）、熱能動能混合（Thermal-Kinetic）、爆破（Explosive）類，以及反外星（AX）武器。

一般而言，在沒有工程師改造介入下，熱能雷射武器適合打能量護盾、動能實彈和爆破武器適合打飛船裝甲

#### 瞄準方式

武器根據瞄準方式分為固定瞄準（Fix）、輔助瞄準（Gimbal）和自動砲塔（Turret）

> 注：
>
> 其實嚴格來說瞄準的三種方式只是其**武器基座類型**，但因為直接影響了瞄準方式因此以這樣方式分類（較易理解）
>
> 因此Gimbal真正意思為『萬象』

可在武器說明看見此分類圖示，左到右分別為：固定瞄準（Fix）、輔助瞄準（Gimbal）和自動砲塔（Turret）

![](https://qiniu.elitedanger.cn/assets/files/2021-04-25/1619328431-129214-weapontypeaim01.jpeg)

* Fix固定瞄準顧名思義，必須完全仰賴玩家對飛船的控制來擊中目標位置
* Gimbal輔助瞄準則是在一定範圍內武器會自動瞄準鎖定的位置
* Turret自動砲塔則是在其射界與射程範圍內，根據設定不同能自動瞄準敵人並發射

除了部分武器為固定瞄準限定之外，大多數武器都有輔助瞄準（Gimbal）和自動砲塔（Turret）的模式

而部分自動砲塔（Turret）模式的武器能開放給多人共乘的玩家Crew使用，有些則倒過來只能由玩家Crew使用，否則視作固定瞄準使用

===

### 武器

武器項目詳情請查看：[【零基础精英入门指南系列】飛船傷害輸出](https://forum.elitedanger.cn/d/770)

#### 挖礦工具

除了武器之外，外部掛點也能安裝挖礦設備。除了深層震波炸藥可間接造成傷害、以及權力遊戲限定的礦矛雷射（Mining Lance）外，挖礦工具皆無法用來攻擊，且不同的挖礦設備有其特殊的使用方式與場合。

* 挖礦雷射（Mining Laser）：挖取小行星表面的碎片用
* 礦矛雷射（Mining Lance，權力遊戲限定）：[權力遊戲解鎖](https://forum.elitedanger.cn/d/331)、能傷害目標的挖礦雷射
* 表層衝蝕礦槍（Abrasion Blaster）：從小行星表面打下礦物儲備用
* 淺層開採飛彈（Sub-surface Displacement Missile）：從小行星淺層挖出礦物儲備用
* 深層震波炸藥（Seismic Charge Launcher）：炸開小行星以挖取礦物儲備

#### 作者: y1n4

## 內建部件

每一艘飛船都有內建部件（Integrated Module）槽位，這些部件沒有重量、不佔用飛船的部件槽，也無法拆除。

內建部件如下：

* 貨艙口（Cargo Scoop）：可[拾取物品](https://forum.elitedanger.cn/d/730)
* 駕駛艙蓋（Canopy）：用以保持駕駛艙的加壓可呼吸環境，會在戰鬥時受損，若完全損壞就會完全爆裂，此時就會使用維生系統的緊急儲備氧氣。
* 三款掃描器分別為：
  * 深空掃描儀（Discovery Scanner），內建『全星系波譜掃描儀』（Full Spectrum System Scanner）
  * 數據連接掃描儀（Data Link Scanner），可[掃描數據點](https://forum.elitedanger.cn/d/728)
  * 短距成分掃描儀（Short Range Composition Scanner），可[掃描有機物或地質物](https://forum.elitedanger.cn/d/728)，上傳至Codex

此外，所有飛船也都有星球降落套組槽（Planetary Approach Suite module slot），默認安裝星球降落套組（Planetary Approach Suite）。

