# installation-Flutter-Mac
記錄如何將安裝 Flutter（Mac）

# 一、安裝教學

## 1. 安裝前提
- 確保你已經安裝了 Xcode 與 Android Studio。
- Android Studio 記得安裝 Plugins（Setting > Plugins）：Dart、Flutter

## 2. 安裝 Flutter SDK
使用 `git clone` 來安裝 Flutter SDK：

```
git clone -b main https://github.com/flutter/flutter.git
```

## 3. 設置環境變數
```
export PATH="$PATH:/輸入你的 Flutter SDK 資料夾路徑/"
```

## 4. 驗證安裝
使用以下命令檢查 Flutter 安裝版本：
```
./flutter/bin/flutter --version
```

## 5. 配置 Android 和 iOS 開發環境
檢查還有哪些東西沒有安裝（如果要 Android 與 ios 都能用，就全部都打勾）
```
flutter doctor
```

# 二、 常見問題
如下圖，比較常遇到問題的，應該是 安裝 CocoaPods 的時候

![CocoaPods.png](./CocoaPods.png)

## 1. 安裝 CocoaPods

使用 Homebrew 安裝 CocoaPods：
```
brew install cocoapods
```

確認是否安裝成功（如果有看到版本號，就是安裝成功囉！）

```
pod --version
```

# 三、最後檢查
```
flutter doctor
```

全部打勾就沒問題了！

![Installation Finish](./installation%20finish.png)

