
# 2020資料創新應用競賽
## 產品或服務構想書

---

# 壹、緣起與創作目的

   根據內政部戶政司截至2020年1月之人口統計資料顯示，台灣65歲以上老年人口約為362萬人，其中獨居老人以及雙老（老老照護）超過百萬人。因此，本團隊希望能藉內政開放資料平台所提供的數據，結合AI、大數據相關技術，開發一套能提供銀髮族相關生活資訊與健康追蹤的APP，讓銀髮族享有資訊科技帶來的便利性。
   隨著台灣人口結構邁入高齡化，銀髮族的安居及照護議題顯然已成為台灣政府的施政重點，同時也是許多社工單位及長照組織關注的焦點。本團隊希望透過APP蒐集銀髮族的生活及健康相關數據（例如：活動地圖軌跡、心率、睡眠、步行數...等），藉由蒐集到的數據提供相關單位進行延伸應用，以提升長照服務的效率及品質。
   
---

## 動機

   對於行動及感官功能開始退化的亞健康年長者，考慮到若使用行動裝置APP在實際使用上會有操作困難，希望能用較人性化的介面，可以主動通知提醒用戶或是依照喜好推薦用戶合適的社交活動以及提供社交活動討論版功能建立交流平台拓展交友圈；針對有慢性疾病的年長者也可以定期紀錄用戶資料作為資料庫，輔助年長者追蹤健康紀錄。

---

# 貳、市場調查與定位 (需含1~2同質性產品或服務比較說明)
經本團隊市場調查過後，台灣針對銀髮族所設計之生活或健康輔助類型的系統相當缺乏，雖然政府提供許多資料及資源，卻礙於沒有任何系統或平台提供整合性的服務，使得資訊過於分散，無法完善提供銀髮族生活所需的便利服務。目前市場上與本團隊較同值性的服務為「台北市銀髮族健康地圖」，針對此服務的說明及分析如下：
*    台北市銀髮族健康地圖
   主要服務：可輸入所在地地址搜尋附近的活動及課程、長青學苑、樂齡學習基地等資訊。
   缺點或不足：
        1. 使用者須主動輸入地址等查詢進行查詢，無法提供適性化的推薦。
        2. 僅提供網頁版，無APP版本，使用者無法透過行動裝置使用該系統。
        3. 缺乏實際參與活動的體驗心得供有興趣的人參考

*    Relive
    主要服務：可以記錄使用者行動軌跡，針對拍照時的位置顯示照片地點
    可改善的功能：
        1. 用語音取代照片，銀髮族可以更簡單的使用
        2. 除了圖片還可以紀錄當地的資訊，例如:真實環境狀況
        
   此外，台灣現今針對社工人員及長照機構所設計的產品或服務相當稀缺，據本團隊實際訪談社工人員後得知，政府目前有提供緊急救護系統，然而此系統所提供的功能較為單一（僅提供緊急通報的服務），對於第一線的社工人員來說，助益十分有限。除了緊急救護系統之外，目前市面上另有商業健康量測產品(小米手環、apple watch...等)可提供相關的健康追蹤資訊，然而這類型產品缺乏資料整合與行為分析功能，並無法達到提昇社工人員工作效率的效果。
   
   本團隊產品與服務將鎖定主要服務客群鎖定於銀髮族群，並運用人工智慧強化便利性（如：行為預測分析,推薦系統,數據挖掘），為雙老的服務機構提供更加智慧化的雲端健康管理及通報系統。

---

# 參、使用對象

1. 可行動自主的銀髮族及長輩
2. 社工單位及關懷人員
3. 銀髮族家屬

---

# 肆、產品或服務特色說明
    
## 產品特色

   推薦系統及推播功能結合地圖功能以供銀髮族群使用，透過數據挖掘以及AI預測分析以便社福單位運用並作為量化參考指標，達到數據驅動決策(Data Driven）之目標。
   
## 服務內容

   透過內政部提供之統計地圖API系統,建立雙老生活服務地圖並以大字體及易懂圖示呈現吸引可行動自主之銀髮族使用，達到推廣之目標。運用政府提供之開放資料，透過機器學習之推薦系統，結合上述API建立銀髮族個性化地圖，依照使用者之需求和個性差異，提供多面向的活動地點以及樂齡學習資訊。同時透過滾動式，不斷更新使用者資訊。亦會將疫病或天氣資料做整理後推播，並於地圖上呈現。最重要的事。另一方面，透過API萃取出手機內部紀錄之健康資訊（如iPhone內的健康功能有步長,睡眠時長等紀錄)，透過AWS機器學習建立預測健康指標之模型。最後將上述更新資料和預測結果以報表和視覺化圖表形式，彙整至社工單位，並交由其相關服務單位作合適的判斷依據。
    
---

# 伍、產品或服務功能(請條列之)

使用客戶為銀髮族群；產品需求對象為關懷單位,長照單位

服務功能
* 被關懷者（銀髮族）
    * 使用者生活地圖介面結合大字體和圖示
    * 氣象及疫病通報：針對使用者(雙老)
    * 社群活動推薦通知
    * 社群活動討論版:提供銀髮族社交平台

* 關懷者（長照單位與關懷機構）
    * 使用者行為分析
    * 銀髮族移動軌跡紀錄和慣性分析
    * 健康狀況監控儀表板
    * 結合衛生福利部提供疫情區域資料提高對該地區銀髮族照護
    * 基於公開資料給予警示加強關注（氣象，地震，全國通報，物資提供）
    * 關懷單位可透過專用使用者介面發送主動推播重要訊息，例如舉辦重要活動訊息。

---

# 陸、未來規劃(如功能擴充等)

* 內政部之 醫療院所/門診/每週看診／可接收人數等資料 / 醫療院所門診位置資訊 / 每周看診人數資料 ->   緊急救護機制 (給救護車的人員等做判斷)，可提供關懷機構及銀髮族警急救援時正確的資訊
* 結合提供之資料，包括醫療院所,門診,每週看診科別,可接收人數等資料，緊急救護機制 (給救護車的人員等做判斷)

* 生活地圖與時事新聞結合：如防疫時結合口罩及藥局位置。


# 資料來源



2. 內政部的氣象（監測站）/疾病公告（週期性）-> 推播
    低溫通知以及疾病公告(e.g.肺炎最新消息)的推播消息可以主動提供給銀髮族最新的資訊提醒出門活動需要注意的事項
    
3. 社會福利 -> 樂齡大學及社區活動 (經緯度位置資訊) -> 推播
    依照銀髮族所在位置推薦附近的社區活動，替活動單位宣傳吸引銀髮族拓展社交圈
    
4. 手機app健康功能 -> 紀錄步行,心率,血壓 -> 提供醫療人員及社工，有異常可以即時提供照護




