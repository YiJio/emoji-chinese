# 表情库 / Emoji Dictionary
这个表情库收集了一些中文社交应用中使用的默认表情。
> This is a dictionary for all default emojis used in some Chinese social apps/platforms.

## 目录 / Table of Contents
* [1. 步骤 / Steps](#步骤--steps)
* [2. 平台 / Platforms](#平台--platforms)
* * [2.1. B站 / BiliBili](#b站--bilibili)
* * [2.2. 抖音 / Douyin](#抖音--douyin)
* * [2.3. QQ](#qq)
* * [2.4. 淘宝 / Taobao](#淘宝--taobao)
* * [2.5. 微信 / WeChat](#微信--wechat)
* * [2.6. 微博 / Weibo](#微博--weibo)
* [3. 注释 / Notes](#注释--notes)
* [4. 其他 / Other](#其他--other)
* [5. 参考 / Sources](#参考--sources)
* [6. 变更日志 / Changelog](#变更日志--changelog)

## 步骤 / Steps
**CDN**
```
https://cdn.jsdelivr.net/gh/YiJio/emoji-chinese@[VER]/[DIR]
```
* `[VER]` -> `1.1.0`（最新/newest）
* `[DIR]` -> `qq`, `wx`, etc.*

~

**Emoji map**

一些让您轻松上手的JSON maps -> `_map`文件夹。都是按照每个应用（主要是网版）打开表情时的顺序。
> There are some emoji maps made easy for you to start in the `_map` directory. These are made in the order shown on the emoji pickers of each app (mostly on the web version).

## 平台 / Platforms

### B站 / BiliBili
![Status](https://img.shields.io/badge/status-somewhat_complete-green)

* *接下来可能会加`热词系列`和`TV系列`表情包。*

`📂 bz`
```
📂 def (默认)
├── 📄 总94、96x96、静态

📂 tv
├── 📄 总44、96x96、动态
├── 📄 总6、96x96、静态
```

### 抖音 / Douyin
![Status](https://img.shields.io/badge/status-not_started-green)

`📂 dy`
```
📂 def (默认)
├── 📄 总？、?x?
```

### QQ
![Status](https://img.shields.io/badge/status-not_complete-green)

QQ分成2003年、2007年、和2011年版。新版跟2015年版一起用。新的表情直接上传到`qq-new`文件夹。
> QQ is separated into 2003, 2007, and 2011 versions. Please use the new version with the 2015 version. Any new emojis will have to be uploaded inside of the `qq-new` directory.

用2003、2007、2011年版表情 -> 请查专门针对这些版本的emoji map。
> Use 2003, 2007, or 2011 emojis -> please look at emoji maps specifically for those.

用QQ新版表情 -> 请看`_map/qqNew.json`（新版+2015年版的表情）。
> Use new emojis -> please look at `_map/qqNew.json` (new + 2015 emojis combined).

`📂 qq`
```
📂 qq-2003 (2003年版)
├── 📄 总96、20x20、动态

📂 qq-2007 (2007年版)
├── 📄 总174、24x24、动态

📂 qq-2011 (2011年版)
├── 📄 总100、56x56、动态

📂 qq-2015 (2015年版)
├── 📄 总139、56x56、动态

📂 qq-new (新版)
├── 📂 def (默认)
│   ├── 📄 总93、56x56、动态【新或从2015年版更新】
├── 📂 small (小表情)
│   ├── 📄 总19、24x24、动态【画风跟2007年的一样】
```

### 淘宝 / Taobao
![Status](https://img.shields.io/badge/status-missing_some-green)

`📂 tb`
```
📂 64x64
├── 📄 总2、静态【只出现在网板】

📂 86x86
├── 📄 总98、静态
```

### 微信 / WeChat
![Status](https://img.shields.io/badge/status-not_complete-green)

微信分成2011版和新版。新的表情直接上传到`wx-new`文件夹。
> WeChat is separated into 2011 version and the new version. Please use the new version's directory for new emojis.

用2011年版表情 -> 请看`_map/wx2011.json`。
> Use 2011 emojis -> please look at `_map/wx2011.json`.

用微信新版表情 -> 请看`_map/wxNew.json`（新版+一些2011年版的表情）。
> Use new emojis -> please look at `_map/wxNew.json` (new + some 2011 emojis combined).

`📂 wx`
```
📂 wx-2011 (2011年版)
├── 📄 总105、48x48、静态

📂 wx-new (新版)
├── 📂 def (默认)
│   ├── 📄 总110、128x128、静态
├── 📂 other (其他)
│   ├── 📂 pc (Windows版)
│   │   ├── 📄 总24、128x128、静态【自带脸红的表情，Windows客户端板专用的】
│   ├── 📂 woap (微信公众平台)
│   │   ├── 📄 总38、64x64、静态【出现在微信公众平台】
```

### 微博 / Weibo
![Status](https://img.shields.io/badge/status-not_complete-green)

以下的文件夹是根据网版微博表情系列而来的。还有一个`tmp`文件夹是仅用于存放特定事件期间放置的临时表情的。这些表情一旦从微博的默认表情列表中消失，我就会把它们放置在此文件夹。
> The below directories follow the emoji series on Weibo's web version. The `tmp` folder is only for temporary emojis that have been placed during certain events on Weibo. Some emojis will be placed in this directory once it is off of Weibo's default emoji list. You can use these in your app anywhere you want by making your custom emoji map.

`wb.json`合并了默认系列和其他系列表情。最新更新时间：2024年2月8号。
> The `wb.json` emoji map combines the default "series" and other "series" emojis. Last updated 2/8/2024.

`📂 wb`
```
📂 def (默认)
├── 📂 36x36
│   ├── 📄 总131、静态
├── 📂 96x96
│   ├── 📄 总100、静态

📂 other (其他)
├── 📂 22x22
│   ├── 📄 总15、动态
├── 📂 36x36
│   ├── 📄 总66、静态
├── 📂 64x64
│   ├── 📄 总4、静态
├── 📂 96x96
│   ├── 📄 总46、静态

📂 tmp (临时)
├── 📂 64x64
│   ├── 📄 总3、静态
├── 📂 96x96
│   ├── 📄 总4、静态
```

## 注释 / Notes
缺少的表情如下 / missing emojis below：

**QQ**
```
新版《大兵》（QQ将名字改为“悠闲”/db）
《汪汪》（/ww）
《扭转乾坤》（/nzqk）
《牛气冲天》（/nqct）
《摸锦鲤》（/mjl）
新版《滚》（QQ将名字改为“请”/gun）
《期待》（/qdqd）
《拜谢》（/bx）
《元宝》（/ybyb）
《牛啊》（/na）
《胖三斤》（/psj）
《好闪》（/hs）
新版《打call》
《变形》
《仔细分析》
《加油》
《菜汪》
《崇拜》
《庆祝》
《吃糖》
《花朵脸》
《我想开了》
《舔屏》
《打招呼》
《酸Q》
《我方了》
《大怨种》
《红包多多》
《你真棒棒》
《大展宏兔》
《福萝卜》
《举牌牌》
《豹富》
《虎虎生威》
《绿马护体》
《右拜年》
《左拜年》
《拿到红包》
《烟花》
新版《爱情》（/aiq）
《汗》（/han）
《打脸》（/dalian）
《击掌》（/jz）
《头撞击》（/tzj）
《甩头》（/st）
《扔狗》（/rg）
《糊脸》（/hulian）
《偷看》（/tk）
《拍桌》（/paizhuo）
《波波》（/bobo）
《扯一扯》（/cheyiche）
《喷脸》（/pl）
《拍头》（/pt）
《舔一舔》（/tyt）
《干杯》（/gb）
《扇脸》（/sl）
《蹭一蹭》（/cengyiceng）
《撩一撩》（/lyl）
《哼》（/heng）
《掐一掐》（/qyq）
《顶呱呱》（/dgg）
《抱抱》（/baobao）
《原谅》（/yuanliang）
《佛系》（/fx）
《拽炸天》（/zzt）
《颤抖》（/chandou）
《生日快乐》（/srkl）
《嘲讽》（/cf）
《开枪》（/kq）
《啃头》（/kentou）
《恭喜》（/gx）
《惊呆》（/jingdai）
《暴击》（/bj）
《拍手》（/ps）
```
**微信**
```
《茶》（[茶][Tea]）
```

## 其他 / Other
如果想帮忙，可以开个PR或写Issue——我有空会查看！
> You are welcome to help by opening up a pull request or write an issue, I can take a look at them!

## 参考 / Sources
* [EmojiAll](https://www.emojiall.com)
* [Emojipedia](https://emojipedia.org)
* [B站](https://bilibili.com)
* [B站图文](https://www.bilibili.com/opus/613279398111932189)
* [淘宝](https://taobao.com)
* [微博](https://weibo.com)

## 变更日志 / Changelog
**[1.4] - 2025/02/15**
* 加了B站的`tv`系列表情。
* 加了淘宝移动版两个缺失的表情。

**[1.3] - 2025/02/08**

![重要](https://img.shields.io/badge/%E9%87%8D%E8%A6%81-f44336) ![Important](https://img.shields.io/badge/Important-f44336)
* 重构了repo -> 为了减少url的长度：
* * 把所有新版表情的文件名都缩写或变成数字了。
* * 把文件夹名字尽量缩写了。

**[1.2] - 2025/02/06**
* 微博emoji map。
* 更新了README。
* 重构了repo。
* 改了些尺寸不一致的文件。

**[1.1] - 2025/02/03**
* 准备了一些emoji maps。
* 添加了 LICENSE。
* 更新了README。
* 重构了repo。
* 上传了‌新的表情。

**[1.0] - 2025/02/01**
* 收集了些表情 -> 还需要将所有文件格式转换为png或gif。