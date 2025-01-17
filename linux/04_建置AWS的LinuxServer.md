# 在AWS建置Linux Server:好處
- 可以只在有需要時， 啟動所需功能及數量的Linux伺服器
- 不需要的Linux 伺服器可於數秒內丟棄。
- 只要幾分鐘時間就能建立起新的Linux 伺服器。
- 當需求改變時，可直接丟棄正在運作中的Linux 伺服器，然後利用範本重新建立伺服器。
- 可直接使用Linux 伺服器而不需擔心硬體管理的問題。
- 可在存取量增加時讓Linux 伺服器自動增加


## [使用AWS 帳戶的免費方案產品]
- 認識[使用AWS 帳戶的免費方案產品](https://aws.amazon.com/tw/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)

## 建立AWS 帳戶:AWS 使用者的個別環境
- 連上AWS 帳戶的建立頁面
  - 輸入電子郵件地址、密碼、帳戶名稱後，按—下〔繼續〕鈕。
  -   密碼必須使用8 個以上不同於電子郵件地址、帳戶名稱的字元，且需包含大寫字母、小寫字母、數字、符號中3 種以上的字元。
  -   輸入於此的電子郵件地址和密碼，將成為AWS 帳戶的root（擁有完整權限可存取所有服務及資源的使用者） 。
  -   root可在AWS 帳戶中執行所有操作，而其他人無法限制其權限。
  -   AWS 帳戶名稱則是以英文字母設定


- 輸入手機號碼
- AWS 將發送簡訊以驗證身份。請確保你的手機處於可接收簡訊的狀態。
- 「手機號碼」不要加連字號（橫線）或括號等符號（例如： 08012345678) 。
- 輸入「安全性檢查」部分所顯示的亂數後，按—下〔傳送簡訊〕鈕。

- 選取支援計劃。
  - 在此是做為學習測試用，故選擇免費的基本方案。
  - 若需要利用技術支援，則可選擇需付費的開發人員計劃。
  - 若要用於正式營運環境者，建議選擇商業計劃
 
- 幾分鐘內就會收到電子郵件，通知你帳戶已完成啟用。

## 設定:安全性和費用有關的設定。
- 有效防止帳戶被盜用
- 避免過度使用導致費用暴增

- 登入AWS 帳戶
  - 選擇以 Root user身份登入，並輸入建立AWS 帳戶時用的電子郵件地址，然後按 [Next]鈕
  - 輸入密碼，再按 [Sign in]鈕
  - 登入成功並進入了管理控制台
- 設定IAM 
  - 於「尋找服務」欄位輸入「iam 」，並移動至IAM 的儀表板。
  - IAM 是用來針對AWS 帳戶內的各個AWS 服務，定義哪些人分別能做些什麼的存取權限設定功能。
  - IAM 儀表板會顯示出各種建議事項
  - [1]最基本且必要的root 的MFA(Multi Factor Authentication,多重驗證) 啟用
  - [2]建立一般的IAM 使用者。
  - MFA(Multi Factor Authentication,多重驗證) 啟用與設定

## 建立IAM 使用者
