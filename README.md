# Swift RSS Reader
RSS Reader application build using Swift, Xcode, and iOS.

## Overview
Swift based RSS Reader that loads ``rss`` feed as an ``xml`` from remote server and parse it using ``NSXMLParser``. Once parsing done, it loads data into ``UITableView`` i.e. shows title and date. When clicked on title it goes to details page where it will browse post url within ``UIWebView``. This is sample rss reader application you can use as a base for any ``RSS Reader`` project and expand it. You can use it free for either personal or commercial use. 

**It consist functionality below:**
+ Fetching ``rss`` feed as ``xml`` from remote server.
+ Parsing ``xml`` using ``NSXMLParser``.
+ Convert ``xml`` into swift based array object.
+ Listing records within ``UITableView``.
+ When clicked on title, it shows details page.
+ Details page will load post url within ``UIWebView``.

![ScreenShot iPhone4](../master/Screenshots/main-1t.png)
![ScreenShot iPhone4](../master/Screenshots/main-2t.png)

## Platform
+ Swift 1.2
+ iOS 8.4
+ Xcode 6.4
+ NSXMLParser

## Supported Device
iPhone 4s, 5, 5s, 5c, 6, 6 Plus, iPad having iOS 8.

## Technology used
+ Table View Controller ``UITableView``.
+ Web view  ``UIWebView``.
+ ``NSXMLParser`` library for ``xml`` data parsing.
+ Simple and Clean interface.
+ Build with Xcode storyboard.
+ Adaptive layout for major screen size support.
+ Created with ``Swift 1.2``, ``iOS 8.4``, ``Xcode 6.4`` and ``NSXMLParser``.

## How To Use

### Setup Data folder
+ Open ``Common.swift`` and set value for ``RSS_FEED_URL``.
<pre>
// RSS Feed URL
let RSS_FEED_URL = "http://www.prashantmangukiya.com/feed/"
</pre>

## Screenshots

**iPhone 4s**

![ScreenShot iPhone4](../master/Screenshots/main-1t.png) &nbsp;&nbsp;
![ScreenShot iPhone4](../master/Screenshots/main-2t.png)

**iPad**

![ScreenShot iPhone4](../master/Screenshots/ipad-1.png)

![ScreenShot iPhone4](../master/Screenshots/ipad-2.png)

## License
SwiftRSSReader is available under the MIT license. See the LICENSE file for more info.
