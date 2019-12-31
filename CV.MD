## Wei-Chun Horng (Jim Hong, 大駿) ##

# 工作經歷

## Software Team Leader, Feb 2017 - Now, Masterwork Aoitek
## Android App Engineer, Nov 2014 - Feb 2017, Masterwork Aoitek
## Software Development Manager, June 2014 - Nov 2014, ThroughTek Co., Ltd
## Section manager, Aug 2009 - April 2014, ASUS

# 自傳
> 大學與研究所在交大資工就讀，在就讀大學期間就發現自己的興趣是寫程式大於學術研究，因此研究所專題選擇進入王協源教授的實驗室，主攻網路模擬器 [NCTUNS](http://csie.nqu.edu.tw/smallko/nctuns/nctuns.htm)，現在是 [EstiNet](https://www.estinet.com/ns/?lang=zh-hant)，我的碩士論文便是在網路模擬器上實現 [802.11p](https://zh.wikipedia.org/wiki/IEEE_802.11p) 智慧行車系統通訊協定。目的是提供模擬器的使用者可以在平台上做相關的研究。碩士論文便是在自己建立的智慧行車系統上研究路由演算法中封包傳遞的效率與實用性。

> 華碩電腦(ASUS)，是我第一份工作，當時是研發替代役身份面試進去，主要是在 Android 手機與平板上對 AsusEmail 做新功能的開發以及維護，AsusEmail 是從 Google 所提供的 [Android Open Source Project](https://source.android.com/) 改進而來，其中包含了 UI 介面調整，Email 通訊協定以及整體架構的修改，在華碩後期擔任到 Email App 的負責人。Trace AOSP Email 的程式碼讓我受益良多。

> 離開 ASUS 之後我想看看其他公司與不同的 Android App，後來便加入了 物聯智慧(ThroughTek)，在這裡主要負責的產品是 Persional Cloud 軟體，曾經在 QT 上研究跨平台解決方案，後來因為公司決策還是回到了 Android 上開發，主要負責的產品是使用 P2P Library 來讓手機連線到私人儲存空間，另外還定義了 App 與韌體間溝通的 Restful API。除此之外改善了 App 端架構，讓 P2P 可以做到一對多。

> 離開 ThroughTek 之後，經由前公司(ASUS)主管介紹，來到了鴻華國際(Masterwork Aoitek)，主要負責的專案是 baby camera，與四位 App 工程師一起從無到有開發產品，產品開發後期(2016 年中) 因為工作需求逐漸往 Backend 發展，2017 年初時 App 開發告一段落，App team 同事也相繼離職，我則留在現職繼續完善 Backend 部分。
> 2017 年初產品在 Amazon 上銷量有起來了，老闆決定要繼續投入人力開發產品便指派我為 Lollipop Software Team Leader，負責招募工程師與管理產品開發，目前負責管理 Frontend, Backend 以及 Android/iOS app 工程師，以及持續專注在 Backend 與 Cloud 架構上做改善。在這裡除了自己軟體開發的實力進步之外，也學習到了經營與管理層面的知識。

# 現況介紹：
> 目前的 Title 是 Lollipop Baby Camera 的 Software Team Lead。

> 主要業務就是管理所有除了跟硬體之外的軟體部分開發，包含前端（網頁，iOS，Android), 後端 (Backend service, Devops)，本身是兼職 Backend engineer。

> Team 上有 8 位工程師，開發模式是敏捷式開發

# 完成了哪些服務
> Camera 和 App 間的溝通大部分都是靠 Backend 串接。
包含帳號處理系統, Restful API, Socket.IO, Streaming(Live/Recording)

## DevOps
* 管理不同 Service，CI/CD
* 將 Server 放部署到不同的 AWS region, 彼此可以透過內網(VPC)互相聯繫，提供更好的使用者體驗
* CloudFront(CDN)
* Mongo db index 調整 -> CPU 使用率 50~60% -> 10%
* 調整 Cloud architecture -> 提升服務使用率，減少帳單花費

### Lollipop Care
* 商業模式定義
* Video recording
* Sleep log

### Lollipop Store
* Stripe
* DHL
* Paypal
* Database Design

### Leader
* 進度安排，人力資源調整，面試
* Standup meeting
* 討論 App 實作架構
* 討論 UX Spec
* 溝通...