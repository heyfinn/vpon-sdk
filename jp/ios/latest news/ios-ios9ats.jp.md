---
layout:         "ios"
title:          "iOS - iOS 9 ATS"
lead:           ""
description:    "The description for this page in the meta data in header."
keywords:       "Keywords for this page, in the meta data"
permalink:       jp/ios/latest-news/ios9ats/
lang:            "jp"
---
# iOS9 ATS
---
## Overview
Apple recently brought a new security feature, App Transport Security (ATS), to iOS9, requiring only HTTPS requests are permitted on iOS9 and above. If you are using the latest Xcode 7 to build or migrate to an iOS9 project, please edit your "info.plist".


## info.plist
To ensure ads continue to serve on iOS9 devices for developers transitioning to HTTPS, the recommended short term fix is to add an exception that allows HTTP requests to succeed and non-secure content to load successfully.

    <key>NSAppTransportSecurity</key>
    <dict>
        <key>NSAllowsArbitraryLoads</key>
        <true/>
    </dict>


## 參考
Links for reference ：

- [Transport Security (ATS)]
- [Ads Developer Blog]


[Transport Security (ATS)]: https://developer.apple.com/library/prerelease/ios/technotes/App-Transport-Security-Technote/|App
[Ads Developer Blog]: http://googleadsdeveloper.blogspot.tw/2015/08/handling-app-transport-security-in-ios-9.html|Google