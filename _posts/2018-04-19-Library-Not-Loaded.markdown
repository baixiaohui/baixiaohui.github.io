---
layout: post
title: Library not loaded
date: 2018-04-19 17:12:32.000000000 +09:00
tags: iOS
---

错误解决：dyld: Library not loaded: @rpath/
解决方法：
1. 退出 Xcode
2. 重启电脑
3. 找到 这个 DerivedData 文件夹 删除 (路径: ~/Library/Developer/Xcode/DerivedData)
4. 删除这个 com.apple.dt.Xcode 文件 (路径: ~/Library/Caches/com.apple.dt.Xcode)
然后 在运行 Xcode 就好了~~