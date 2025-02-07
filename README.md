# 表情库 (Emoji Dictionary)
这个表情库收集了一些中文社交应用中使用的默认表情。（注意：想着也收集抖音的表情吧）。
> This is a dictionary for all default emojis used in some Chinese social apps. (Note: Thinking of also adding Douyin's emojis).

## 目录 (Table of Contents)
* [1. 概述 (Overview)](#概述-overview)
* * [1.1. B站（BiliBili）](#b站bilibili)
* * [1.2. QQ](#qq)
* * [1.3. 淘宝（Taobao）](#淘宝taobao)
* * [1.4. 微信（WeChat）](#微信wechat)
* * [1.5. 微博（Weibo）](#微博weibo)
* [2. 注释 (Notes)](#注释-notes)
* [3. 其他 (Other)](#其他-other)
* [4. 参考 (Sources)](#参考-sources)
* [5. 变更日志 (Changelog)](#变更日志-changelog)

## 概述 (Overview)
**CDN**
```
https://cdn.jsdelivr.net/gh/YiJio/emoji-chinese@[VER]/[DIR]
```
*`[VER]` -> `1.0.0`（最新/newest）
*`[DIR]` -> `qq`, `wechat`, etc.*

**Emoji map**

准备了一些emoji maps（让您轻松上手），请查看`_emoji_maps` directory。复制到您的APP后怎么修改就怎么修改！我之后可能会把这些maps缩小化。
> I prepared some emoji maps (easy for you to start), please take a look at the `_emoji_maps` directory. You can change the contents of the JSON objects however you like in your app. I might also make them a minified js/json file later.

---

### B站（BiliBili）
* *或许会加`热词系列`和`TV系列`表情包。*
```
📂 default (默认)
├── 📄 96x96：总共94个静态表情。
```

### QQ
QQ里面的表情分成2003年、2007年、和2011年版。2015年版开始了新的默认表情设计，所以新版directory（`qq-new`）只是一些被改了或换了名字的表情。如果一个表情的形象或名字被改了，直接上传到这个directory就好。
> QQ is separated into 2003, 2007, and 2011 versions. The 2015 version is the start of the new emoji look, but some emojis have either been designed or renamed. Any new emojis can be placed inside of the `qq-new` directory. If there is a new design or name for the emoji, you can upload the new version into the new directory as well.

如果想要用我准备好的emoji map的话，把map复制到您的APP后记得也修改一下表情的directory/url哦。（注意：只有在①有新的表情上传了且我尚未更新emoji map时，②或者您想使用2003、2007、2011年的表情包时，才这样做）。
>  If you are using any of the emoji maps I have prepared, don't forget to also update the emoji's directory/url when you copy the map to your app! (Note: Only do this ① if there are new emojis and I have not updated the maps, OR ② if you want to use 2003, 2007, or 2011 emojis).

```
📂 qq-2003 (2003年版)
├── 📄 20x20：总共96个动态表情。

📂 qq-2007 (2007年版)
├── 📄 24x24：总共174个动态表情。

📂 qq-2011 (2011年版)
├── 📄 56x56：总共100个动态表情。

📂 qq-2015 (2015年版)
├── 📄 56x56：总共139个动态表情。

📂 qq-new (新版)
├── 📂 default (默认)
│   ├── 📄 56x56：总共94个新或从2015年版更新了的动态表情。
├── 📂 small (小表情)
│   ├── 📄 24x24：总共19个动态表情（画风跟2007年的一样）。
```

### 淘宝（Taobao）
```
📂 64x64
├── 📄 64x64：总共2个静态表情（只出现在网板）。

📂 86x86
├── 📄 86x86：总共96个静态表情。
```

### 微信（WeChat）
微信里面的表情有2011版和一个新版directory（`wechat-new`）。请用这个新directory。（注意：这些表情都不是动态的……我正在想办法把动态的弄到手……）。
> WeChat is separated into 2011 version and the new version. Please use the new version's directory. (Note: The emojis are not animated... still trying to think of a way to get my hands on them...).

```
📂 wechat-2011 (2011年版)
├── 📄 48x48：总共105个静态表情。

📂 wechat-new (新版)
├── 📂 default (默认)
│   ├── 📄 128x128：总共110个静态表情。
├── 📂 other (其他)
│   ├── 📂 pc (Windows版)
│   │   ├── 📄 128x128：总共24个自带脸红的表情。这个是Windows客户端板微信专用的。用的话在emoji map里换directory/url哦。
│   ├── 📂 woap (微信公众平台)
│   │   ├── 📄 64x64：总共38个出现在微信公众平台的表情（稍微有点不同的细节的）。用的话在emoji map里换directory/url哦。
```

### 微博（Weibo）
```
📂 default (默认)
├── 📂 36x36
│   ├── 📄 36x36：总共196个静态表情（并非全套，有些96x96里面没有的）。
├── 📂 96x96
│   ├── 📄 96x96：总共149个静态表情（并非全套，有些36x36里面没有的）。
├── 📄 还有4个64x64的静态表情。

📂 small (小表情)
├── 📄 22x22：总共15个动态表情。
```

## 注释 (Notes)
想要帮忙吗？可以先看看下面缺少的表情哦！您也可以完成微博的表情包。
> Want to help out? You can first look at the missing emojis below as a start! You are welcome to finish the Weibo emoji collection too.

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
**淘宝**

下面的只出现在手机版：
```
《太难了》（/:""）
《好累》（/:"）
```
**微博**

这个看96x96和36x36的区别。
> You can look at what is missing between the 96x96 and 36x36 versions.


## 其他 (Other)
您只需要开个PR上传更多的表情，我回来看会合并的。
> You are welcome to add more emojis to the list by opening up a pull request and I can merge them.

如果您发现任何问题，也可以开Issues，我会查看！
> If you find any other problems, you can also open an issue and I will look at it!

如有其他问题，请联系`network@yijione.com`。谢谢。
> If you have other questions, you can contact `network@yijione.com`. Thank you.

## 参考 (Sources)
* [EmojiAll](https://www.emojiall.com)
* [Emojipedia](https://emojipedia.org)
* [B站](https://bilibili.com)
* [B站图文](https://www.bilibili.com/opus/613279398111932189)
* [淘宝](https://taobao.com)
* [微博](https://weibo.com)

## 变更日志 (Changelog)
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
