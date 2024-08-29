---
title: '在「Mac OS」上完整移除「IntelliJ IDEA」的設定檔、暫存檔'
alias: 'rm-intellij-settings'
category: '填坑日常'
tags: [IDE, 環境設定]
---

# 在「Mac OS」上完整移除「IntelliJ IDEA」的設定檔、暫存檔

![](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb)

---

> [!Tip]
> 如題，記錄一下要如何在「Mac OS」上完整移除「IntelliJ IDEA」的設定檔、暫存檔。

---

## 前言

之前由於某些原因，需要完整移除「Macbook」中「IntelliJ IDEA」，一時間找不到它預設存放偏好設定檔、暫存檔的路徑，紀錄一下。

## 正文

提醒一下，筆者不能肯定所有版本的「IntelliJ IDEA」的設定檔、暫存檔的預設路徑都一致，印象中，好像有變更過，但不論如何，筆者目前所使用的「IntelliJ IDEA」的版本是如此，筆者目前使用的「IntelliJ IDEA」的版本是「2022.1.4」，其預設的存放位置ㄧ共有四個地方，如下：

```shell
rm -rf /Users/{username}/Library/Preferences/jetbrains.jetprofile.asset.plist
rm -rf /Users/{username}/Library/Caches/JetBrains
rm -rf /Users/{username}/Library/Application\ Support/JetBrains
rm -rf /Users/{username}/Library/Logs/JetBrains
```

備註：「`{username}`」為「使用者」的電腦名稱。

擔心自己的金魚腦，記錄一下，「Joe4John」，收工！

## 參考資料

- [Jetbrains IntelliJ IDEA Help](https://www.jetbrains.com/help/idea/configuring-project-and-ide-settings.html)
