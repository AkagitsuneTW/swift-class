# Swift 學習筆記與練習

這是個人用來學習 Swift 的專案，透過實作與練習，逐步熟悉 Swift 語法、SwiftUI 介面開發，以及 iOS App 的基本架構。

## 學習方向

- Swift 基礎語法：變數、型別、流程控制、函式與 Optional。
- 資料建模：結構、類別、列舉與協定。
- SwiftUI：畫面布局、元件組合、狀態管理與畫面導覽。
- 透過小型功能練習，記錄學習過程中的心得與問題。

## 目前內容

目前以 SwiftUI 的「Hello, world!」畫面作為起點，後續會隨著學習進度加入更多練習。

## 專案結構

```text
swift-class/
├── README.md
├── swift-class.xcodeproj/       # Xcode 專案設定
└── swift-class/
    ├── swift_classApp.swift     # App 進入點
    ├── ContentView.swift        # 主畫面
    └── Assets.xcassets/         # 圖片與色彩資源
```

## 開始練習

1. 使用 macOS 上的 Xcode 開啟 `swift-class.xcodeproj`。
2. 選擇 `swift-class` Scheme 與可用的 iOS 模擬器或實體裝置。
3. 按下 `⌘R` 建置並執行，或使用 SwiftUI Preview 預覽畫面。

目前專案的 iOS Deployment Target 設為 **27.0**，請使用支援此版本的 Xcode 與執行環境；若需在較舊的系統執行，可依練習內容調整 Deployment Target。

## 學習紀錄

每次練習可記下學習主題、實作內容、遇到的問題與解法，方便日後回顧。
