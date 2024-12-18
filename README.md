# 碳排放計算器

## 介紹

碳排放計算器是一個 Flutter 應用程式，幫助用戶追蹤每日的碳排放減少量，並養成環保習慣。該應用與 Firebase 整合，用於用戶認證和資料存儲。

---

## 功能

### 碳排放目標

用戶可以選擇完成以下環保行動，並查看所減少的碳排放量：
- **步行或騎腳踏車上班**：減少 2.5 公斤碳排放。
- **使用環保購物袋**：減少 0.5 公斤碳排放。
- **關閉不必要的電器**：減少 1.2 公斤碳排放。
- **吃素一餐**：減少 3.0 公斤碳排放。
- **減少使用冷氣**：減少 2.0 公斤碳排放。
- **使用大眾交通工具**：減少 3.5 公斤碳排放。
- **不用一次性塑膠餐具**：減少 0.8 公斤碳排放。
- **節約用水**：減少 1.5 公斤碳排放。

### Firebase 整合

- **用戶註冊與登入**：
  - 使用 Firebase Authentication 進行用戶認證。
  - 支援電子郵件和密碼註冊。
- **用戶登出**：
  - 用戶可以從應用程式中登出。

---

## 安裝與執行

### 環境需求
- **Flutter SDK**: 最新穩定版
- **Firebase 設定**:
  - Firebase Authentication 已啟用。
  - 將 `google-services.json` 放置於 `android/app` 資料夾。
  - 將 `GoogleService-Info.plist` 放置於 `ios/Runner` 資料夾。

### 安裝步驟

1. Clone 此專案到本地端：
   ```bash
   git clone <>
   ```

2. 進入專案目錄：
   ```bash
   cd carbon-footprint-calculator
   ```

3. 安裝相依套件：
   ```bash
   flutter pub get
   ```

4. 運行應用程式：
   ```bash
   flutter run
   ```

---

## 使用說明

1. **註冊或登入**：
   - 開啟應用程式，並使用電子郵件與密碼進行註冊或登入。

2. **選擇目標**：
   - 勾選已完成的環保行動，系統會自動計算今日減少的碳排放總量。

3. **登出**：
   - 點擊右上角的登出按鈕即可登出帳號。

---

## 專案結構

```
carbon-footprint-calculator/
├── android/               # Android 平台相關檔案
├── lib/                   # Flutter 應用程式主要程式碼
│   ├── login.dart         # 登入頁面
│   ├── signup.dart        # 註冊頁面
│   ├── carbon.dart        # 碳排放目標頁面
│   ├── wrapper.dart       # 用戶狀態管理
│   └── main.dart          # 主入口文件
├── pubspec.yaml           # Flutter 套件配置檔案
└── README.md              # 專案說明文件
```

---

## 開發者

此應用程式由 [u06d93] 開發，旨在提高環保意識，促進碳排放減少。

歡迎提出建議與改進！

---
