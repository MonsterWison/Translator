# Vibe Coding 課程教材
# Vibe Coding class material

狀態：進行中 截止日期：06/17/2025 ID：27 💼 專案：VTX - Cohort 3 (https://www.notion.so/VTX-Cohort-3-1fa35af00755802fbdf0ec5d149f2c52?pvs=21)
Status: In progress Due date: 06/17/2025 ID: 27 💼 Projects: VTX - Cohort 3 (https://www.notion.so/VTX-Cohort-3-1fa35af00755802fbdf0ec5d149f2c52?pvs=21)

iOS 應用程式 Vibe Coding
iOS app Vibe Coding

## 所需軟體
## Software required
	•	XCode
	•	XCode 模擬器 / XCode Simulator
	•	https://www.cursor.com/
	•	https://brew.sh/
	•	Cursor 設定參考 / Cursor setup reference
	•	https://dimillian.medium.com/how-to-use-cursor-for-ios-development-54b912c23941

brew install xcode-build-server

brew install xcbeautify

brew install swiftformat

# Sweetpad：生成建構伺服器配置
# Sweetpad: Generate Build Server Config

## 大綱
## Outline

### 環境設定
### Environment Setup
	•	使用 XCode 創建新專案 / Create new project using XCode
	•	確保 iOS 模擬器正確安裝 / Ensure iOS simulator is properly installed
	•	Cursor 擴充功能設定 / Cursor extension setup
	•	嘗試在 Cursor 中運行專案 / Try to run the project in Cursor

### 如何「教導」Cursor
### How to 'teach' Cursor
	•	專案文檔 / Project documentation
	•	Cursor 規則 / Cursor Rules
	•	選擇正確的模板 / Pick the right template https://cursor.directory/rules
	•	SwiftUI https://cursor.directory/swiftui-swift-simple-developer-cursor-rules
	•	文檔 / Documentation

### 開始前需要了解的內容
### Learning what you're doing before start
	•	應用程式開發流程 / App development process
	•	低保真 UI（線框圖）/ Low fidelity UI (wireframe)
	•	高保真設計 / High fidelity design
	•	使用者體驗 / UX
	•	元件設計 / Component design
	•	畫面實作 / Screen implementation
	•	軟體架構 / Software Architecture
	•	https://medium.com/learn-record/mvc-mvp-mvvm%E6%9E%B6%E6%A7%8B%E6%AF%94%E8%BC%83-62b5657d2e21
	•	https://developer.apple.com/documentation/swift/choosing-between-structures-and-classes
	•	https://developer.apple.com/design/human-interface-guidelines
	•	自定義準則 / Custom guidelines
	•	iOS 版本和 XCode 版本 / iOS version and XCode version
	•	Apple 框架 / Apple Framework
	•	專案管理 / Project Management
	•	Info.plist
	•	平台 / Platform
	•	最低 iOS 版本 / Minimum iOS version

你是一位使用 Swift 和 SwiftUI 的專業 iOS 開發者。請遵循以下準則：
You are an expert iOS developer using Swift and SwiftUI. Follow these guidelines:

## 程式碼結構
## Code Structure

- 使用 Swift 的最新功能和協定導向程式設計
- Use Swift's latest features and protocol-oriented programming

- 優先使用值類型（結構）而非類別
- Prefer value types (structs) over classes

- 使用 MVVM 架構搭配 SwiftUI
- Use MVVM architecture with SwiftUI

- 結構：Features/、Core/、UI/、Resources/
- Structure: Features/, Core/, UI/, Resources/

- 遵循 Apple 的人機介面指南
- Follow Apple's Human Interface Guidelines

## 命名規則
## Naming

- 變數/函數使用駝峰式命名法，類型使用帕斯卡命名法
- camelCase for vars/funcs, PascalCase for types

- 方法使用動詞（fetchData）
- Verbs for methods (fetchData)

- 布林值：使用 is/has/should 前綴
- Boolean: use is/has/should prefixes

- 遵循 Apple 風格的清晰、描述性命名
- Clear, descriptive names following Apple style

## Swift 最佳實踐
## Swift Best Practices

- 強型別系統，適當使用可選型別
- Strong type system, proper optionals

- 使用 async/await 處理非同步
- async/await for concurrency

- 使用 Result 型別處理錯誤
- Result type for errors

- 使用 @Published、@StateObject 管理狀態
- @Published, @StateObject for state

- 優先使用 let 而非 var
- Prefer let over var

- 使用協定擴展共享程式碼
- Protocol extensions for shared code

## UI 開發
## UI Development

- 優先使用 SwiftUI，必要時使用 UIKit
- SwiftUI first, UIKit when needed

- 使用 SF Symbols 作為圖示
- SF Symbols for icons

- 支援深色模式、動態字型
- Support dark mode, dynamic type

- 使用 SafeArea 和 GeometryReader 進行佈局
- SafeArea and GeometryReader for layout

- 處理所有螢幕尺寸和方向
- Handle all screen sizes and orientations

- 實作適當的鍵盤處理
- Implement proper keyboard handling

## 效能
## Performance

- 使用 Instruments 進行效能分析
- Profile with Instruments

- 延遲載入視圖和圖片
- Lazy load views and images

- 最佳化網路請求
- Optimize network requests

- 背景任務處理
- Background task handling

- 適當的狀態管理
- Proper state management

- 記憶體管理
- Memory management

## 資料與狀態
## Data & State

- 使用 CoreData 處理複雜模型
- CoreData for complex models

- 使用 UserDefaults 儲存偏好設定
- UserDefaults for preferences

- 使用 Combine 進行響應式程式設計
- Combine for reactive code

- 清晰的資料流架構
- Clean data flow architecture

- 適當的依賴注入
- Proper dependency injection

- 處理狀態還原
- Handle state restoration

## 安全性
## Security

- 加密敏感資料
- Encrypt sensitive data

- 安全使用 Keychain
- Use Keychain securely

- 憑證綁定
- Certificate pinning

- 必要時使用生物辨識驗證
- Biometric auth when needed

- 應用程式傳輸安全性
- App Transport Security

- 輸入驗證
- Input validation

## 測試與品質
## Testing & Quality

- 使用 XCTest 進行單元測試
- XCTest for unit tests

- 使用 XCUITest 進行 UI 測試
- XCUITest for UI tests

- 測試常見使用者流程
- Test common user flows

- 效能測試
- Performance testing

- 錯誤情境
- Error scenarios

- 無障礙測試
- Accessibility testing

## 基本功能
## Essential Features

- 深層連結支援
- Deep linking support

- 推播通知
- Push notifications

- 背景任務
- Background tasks

- 在地化
- Localization

- 錯誤處理
- Error handling

- 分析/記錄
- Analytics/logging

## 開發流程
## Development Process

- 使用 SwiftUI 預覽
- Use SwiftUI previews

- Git 分支策略
- Git branching strategy

- 程式碼審查流程
- Code review process

- CI/CD 流程
- CI/CD pipeline

- 文檔
- Documentation

- 單元測試覆蓋率
- Unit test coverage

## App Store 指南
## App Store Guidelines

- 隱私描述
- Privacy descriptions

- 應用程式功能
- App capabilities

- 應用程式內購買
- In-app purchases

- 審查指南
- Review guidelines

- 應用程式瘦身
- App thinning

- 適當的簽署
- Proper signing

請參考 Apple 文檔以獲取詳細的實作指南。
Follow Apple's documentation for detailed implementation guidance.

## SwiftUI 基礎
## SwiftUI Fundamentals
	•	視圖 / View
	•	堆疊 / Stack
	•	SwiftUI vs. UIKit
	•	CoreData vs SwiftData
	•	Apple 框架 / Apple Framework：https://developer.apple.com/documentation/

## 一般開發指南
## General Development Guideline
	•	總是先做 UI 模型，在所有 UI 準備好之前不要實作任何程式邏輯
	•	Always do UI mockup first, do not implement any code logic until all UI are ready
	•	做 UI 時要始終考慮資料模型
	•	Always think about the data model when doing UI
	•	將資料模型與相應的框架資料類型進行比較
	•	Compare data model with corresponding framework data type
	•	選擇最有價值的使用者旅程來實作
	•	Pick the most valuable user journey to implement
	•	使用 Mobbin 產生 UI 想法 / Use Mobbin to generate UI idea https://mobbin.com/discover/apps/ios/latest

## 提示工程指南
## Prompt Engineering Guideline
	•	一般 / General
	•	準備 project.md / Prepare project.md
	•	對於短期計劃，例如清理，準備單獨的 cleanup.md
	•	For short term plan, e.g. cleanup, prepare a separate cleanup.md
	•	與 Cursor 交談就像他在與你一起工作在同一個專案上
	•	Talk to Cursor as if he's working on the same project with you
	•	在執行之前討論和計劃要做什麼，暫時不要進行程式碼更改
	•	Discuss and plan on what to do before doing, add do not make code change yet
	•	討論解決方案時提供 @docs 和 @web。提醒 Cursor 遵循最佳實踐
	•	Provide @docs and @web when discussing on solutions. Reminds Cursor about following best practice
	•	實作程式碼更改時，要求分解成多個步驟
	•	When implement code change, ask to break down in multi-steps
	•	提醒他有 cursor 規則要遵循
	•	Remind him there is cursor rules to follow
	•	提供尋找解決方案的文檔
	•	Provide documentation on finding solution
	•	除錯 / Debugging
	•	Cursor 如何除錯？⭐ / How Cursor debug? ⭐
	•	除錯時提供截圖 / Provide screenshots when debugging
	•	除錯時提供控制台輸出 / Provide console output when debugging
	•	為除錯目的添加控制台輸出 / Add console output for debugging purpose
	•	程式碼品質 / Code quality
	•	在實際實作階段時不時要求清理和重構
	•	Occasionally ask for clean up and refactoring, usually in actual implementation stage
	•	密切關注程式碼如何實作，特別是是否符合 MVVM
	•	Watch closely how the code is being implemented, especially whether it complies with MVVM
	•	當有疑問時質疑實作方法並要求證據
	•	Question implementation approach when in doubt and request for evidence
	•	在過程中學習 ⭐ / Learn along the way ⭐

## 參考資料
## Reference
https://www.youtube.com/@seanallen

https://www.youtube.com/@ChaoCode

https://youtube.com/playlist?list=PL8h9yRGN7VETh72--p-AUbDNbuk_vTtD9&si=8ySTG5PR6qVbE2-z 