# 帮助文档

【温馨提醒】 *本帮助可以在“**我的**”——右上角帮助按钮再次打开，更新前一定要做好备份，以免数据丢失！*

### 首次安装请点击以下按钮初始化书源

# [点击导入书源](yuedu://booksource/importonline?src=https://gitee.com/cyh92/StaticPage/raw/master/book/book-1400.json)

## 新人必读 

### 1. 为什么第一次安装好之后什么东西都没有？
阅读只是一个转码工具，不提供内容。

### 2. 正文出现缺字漏字、内容缺失或排版错乱等情况，如何处理？
有可能是净化规则出现问题，先关闭替换净化并刷新，再观察是否正常。如果正常说明净化规则存在误杀，如果关闭后仍然出现相关问题，请点击源链接查看原文与正文是否相同，如果不同，再进行反馈。

### 3. 漫画源看书显示乱码，如何解决？
【异次元】和【阅读】是两个不同的软件，**两个软件的源并不通用**，请导入【阅读】的支持的漫画源！

## 书源相关

### 1. 如何导入本地书源文件？
以导入 QQ 接收到的书源文件为例：
* 下载群文件里的书源文件；
* 打开【阅读】软件；
* 点击“**我的**”——“**书源管理**”；
* 点击右上角选择“**本地导入**”；
* 左下角选择书源文件所在的路径；
* 点击书源文件导入；
* 导入后返回书源管理界面；

**【注】** 
1. *新版 QQ 文件下载路径：`Android/data/com.tencent.mobileqq/Tencent/QQfile_recv/`。*
2. *书源格式后缀有 .txt 和 .json，其中 .json 文件在某些情况下可能无法导入，需要修改后缀为 .txt 才可导入。*

![QQ 导入书源](https://cdn.jsdelivr.net/gh/gedoor/gedoor.github.io@master/images/importSource.jpg)

### 2. 如何新建大佬发的单独书源？
* 复制书源代码；
* 打开阅读软件；
* 点击“**我的**”——“**书源管理**”；
* 右上角“**⁝**”——“**+ 新建书源**”；
* 进入后点击右上角“**⁝**”——“**粘贴源**”；
* 粘贴完成后点击上方保存“**🖫**”按钮；
* 本次新建单独书源操作完成。

**【注】** *如果书源有错误或者复制不全会显示格式错误，请重新复制。*

### 3. 为什么导入 2.0 书源后无法阅读？
部分 2.0 书源并不适用于 3.0 版本的阅读，建议导入后进行筛选。

### 4. 【阅读】2.0 数据如何导入【阅读】3.0？
先对【阅读】2.0 的数据进行备份，然后进入【阅读】3.0，点击“**我的**”，选择“**备份与恢复**”，再点击“**导入旧版本数据**”。

### 5. 如何给朋友分享我的书源？
* 打开【阅读】软件；
* 点击备份；
* 打开手机系统自带的文件管理；
* 在手机内置存储根目录找到 `YueDu3.0` 文件夹；
* 找到 `myBookSource.json`，长按选择分享；
* 选择微信分享或者 QQ 分享；
* 选择你要分享的好友点击发送；
* 好友接收后在手机内置存储根目录找到 `myBookSource.json` 文件；
* 复制该文件到手机内置存储根目录找到 `YueDu3.0` 文件夹（如已有该文件请先删除该文件或者备份到其他地方再复制到文件夹）；
* 打开【阅读】软件点击恢复。

**【注】**
1. *备份路径如已修改过请在修改后的路径下查找书源文件。*
2. *Android 10 及以下版本系统，新版 QQ 文件接收路径在 `Android/data/com.tencent.mobileqq/Tencent/QQfile_recv/`，旧版 QQ 文件接收路径则在 `Tencent/QQfile_recv/`；新版微信文件接收路径在 `Android/data/com.tencent.mobileqq/Tencent/MicroMsg/Download`，旧版微信文件接收路径则在 `Tencent/MicroMsg/Download`。*
3. *Android 11 及以上系统版本用户，由于系统限制，无法访问 `Android/data` 目录。*

### 6. 效验书源显示失效就说明书源不能用了吗？
效验书源只是测试书源，可以做为参考，但失效了不代表书源不能用了。

### 7. “发现”和正版书源能不能使用？
发现和正版书源只能用来找书或看排行榜，不能用来看书，如需看书请切换书源。

### 8. 为什么书源这么多，“发现”里却只有一点点？
书源想要在发现界面里显示需要在书源里添加发现规则，并不是所有书源都有发现规则。

## 本地/WebDav远程书籍相关

### 1. 目前阅读支持哪些格式的本地书籍？
目前支持 TXT 和 EPUB 格式。

### 2. 如何导入本地/WebDav远程书籍？
本地：在书架页面点击右上角“**⁝**”，选择“**添加本地**”，授予相关权限后即可导入本地书籍。也可在文件管理器中使用【阅读】打开相关书籍。

远程：在主页面点击右上角 “**⁝**”，选择 **WebDav书籍**，正确配置好后即可看到上传的远程书籍，点击 **加入书架** 按钮导入即可。

### 3. 如何上传本地书籍到 WebDav 远程？
长按本地书籍，进入书籍详情页，点击右上角 “**⁝**”，选择 **上传WebDav**，等待几秒后即可上传到远程。

或进入书籍缓存页面，点击右上角 “**⁝**”，选择 **导出到 WebDav**，在书籍导出时便可同时上传到远程。

### 4. 导入 TXT 文件提示“LoadTocError”或“List is empty”是怎么回事？
* 请先去应用详情中确认是否授予了【阅读】“读写手机存储”的权限。
* 自动识别目录失败，可能是相关目录规则未开启，请点击右上角的换源按钮手动更换目录规则。

如果尝试所有规则均无法识别，请在 GitHub 上提交 Issue 并附上相关 TXT 文件，也可以发送邮件至 i@qnmlgb.trade（标题：legado 本地文件章节无法识别；内容对其具体情况进行简要说明，附件上传相关 TXT 文件）。

### 5. 如何下载书籍到本地？
把在线书籍加入到书架后，在书架页面点击右上角，选择“**离线缓存**”即可。

### 6. 如何自定义导出的 TXT 或 EPUB 文件名称？
* 点击“**离线缓存**“——”**导出文件名**“
* 使用方法:
  - 导出文件名支持 js 语法
  - 可用变量: name（书名）和 author（作者）
  - 示例:
  > name + "作者:" + author
  - 导出文件名:
  >  Legado 是最好的在线阅读软件 作者: kunfei

**【注】** *name、author 等变量与字符串的拼接都需要在 JSON 上下文环境中进行，即必须使用 `{}` 将变量与字符串包裹起来。*

### 7. 为什么我打开本地的 TXT 文件，显示内容却是乱码？
部分编码在阅读上会识别错误，建议先用文本编辑器转换为常用的 UTF-8 格式。

### 8. 阅读对部分把正文（如所有含引号的句子）识别成标题，如何解决？
点击右上角更换目录规则即可。

## 书籍界面相关

### 1. 如何刷新书架？
在书架界面下拉即可刷新。

### 2. 书架界面书籍右上角的红色或者灰色背景小数字代表什么？
红色代表书籍有更新，灰色代表无更新，数字代表未读章节。

### 3. 如何查看书籍详情？
长按书籍即可查看。

### 4. 如何对书架上的书进行删除、切换书架的操作？
书籍详情页操作即可。

### 5. 如何禁止或允许某本书更新？
书籍详情页，点击右上角——“**允许更新**”。

### 6. 如何更换小说封面、名字、作者或简介？
书籍详情页，点击右上角修改按钮。

### 7. 怎么使用自定义字体？
阅读界面——“**字体**”——点击右上角选择字体文件路径。

### 8. 目前支持哪些格式的字体文件？
目前支持 TTF 和 OTF 格式。

### 9. 书籍经常“正在加载中”怎么办？
在线书籍出现这个问题通常是由于源质量不好或不兼容引起的，可以换其它源多试试；本地书籍出现这个问题大概率是目录规则问题，手动切换规则可以解决。

### 10. 书籍内容只有标题，正文内容是路径怎么办？
通常是缓存路径引起的，更换缓存路径即可。

### 11. 看书时如遇到“目录为空”、“加载失败”或长串英文等情况怎么办？
在线书籍一般是书源问题，切换或更新书源即可。本地书籍请尝试手动更换目录规则。

### 12. 为什么每一章的最后一页，阅读的文字和横线背景总是对不齐？
请在“**设置**”——“**文字底部对齐**”选项中关闭底部对齐，再调整排版。

### 13. 漫画源或图片章节只能看到第一页，如何解决？
请先查看原网页是否正常，若正常，请在书籍阅读界面点击右上角的“**⁝**”按钮，在弹出的菜单中，选择“**翻页动画(本书)**”，将翻页动画更改为“**滚动**”。

### 14. 阅读图片章节、漫画或 EPUB 插图时，图片被缩放到一页中，以至无法看清，如何处理？
* 临时处理方案：长按图片可以进行双指缩放。图片章节请先参考 Q13 中的方案将翻页动画更改为“**滚动**”。
* 3.0 旧版可以点击书籍界面的章节标题进入“**编辑书源**”界面，在“**正文**”——“**图片样式**”中填入 *`full`*，保存更改，刷新当前章节即可。
* 3.0 新版可以直接在书籍阅读界面点击右上角的“**⁝**”按钮，选择“**图片样式**”——***`full`***。


## 替换净化相关

### 1. 替换净化是什么？
替换净化可以去除书籍内容里的广告、错别字、屏蔽词等。

### 2. 如何自己填写净化替换规则？
* 第一行：替换规则名称。请根据自己需求对替换净化规则进行命名；
* 第二行：分组。净化规则的分组组别；
* 第三行：替换规则。填写需要被替换的内容；
* 第四行：替换为。填写想替换成的内容（如不填则默认表示删除第三行里填写的内容）；
* 第五行：替换范围，选填书名或者源名。填写此替换净化规则需要对哪本书籍或者哪个书源生效（如不填则对所有书籍和书源生效）。

**【注】** *如常规去除方法去除不掉，则需要勾选“使用正则表达式”，同时第三行里的替换规则也需要按照正则表达式来填写（正则表达式填写方法可自行网上搜索学习）。*


## 备份相关

### 1. 云备份在哪？
“**我的**”——“**备份与恢复**”——“**WebDav 设置**”。

### 2. 如何操作进行云备份？
* 侧栏设置，WebDav 设置；
* 正确填写 WebDAV 服务器地址、账号和密码；
* 无需操作，APP 默认每天自动云备份一次。

作者在此诚挚推荐使用【坚果云】进行 WebDav 备份。

如果直接在手机上注册，须下载【坚果云】APP，步骤较为繁琐。推荐在电脑上进行操作：
1. 打开注册链接：https://www.jianguoyun.com/d/signup ；
2. 注册后，进入坚果云；
3. 点击右上角账户名处选择“**账户信息**”，然后选择“**安全选项**”；
4. 在“**安全选项**”中找到“**第三方应用管理**”，并选择“**添加应用**”，输入名称（如“阅读”）后，会生成密码，选择完成；
5. 其中 `https://dav.jianguoyun.com/dav/` 就是填入“**WebDAV 服务器地址**”的内容，“**使用情况**”后面的邮箱地址就是你的“**WebDAV 账号**”，点击“**显示密码**“后得到的密码就是你的“**WebDAV 密码**”。

### 3. 关于云备份的相关说明

在正确设置好云备份的情况下，APP 默认每天自动云备份一次，当日多次手动云备份会对当日的旧云备份文件进行覆盖，并不会覆盖之前及之后不同日期的备份文件，每天所自动云备份的文件会按照日期进行命名。

### 4. 本地备份和云备份都能备份哪些东西？
书架、看书进度、搜索记录、书源、替换和 APP 设置等都会备份，基本涵盖所有内容。

### 5. 出现某些未知 Bug 怎么办？
清除软件数据试试看，不行再进行反馈。


## 其他

### 1. 如何听书？
可以使用手机自带的朗读引擎，也可使用第三方如 Google（谷歌）或小米等朗读引擎。

【具体操作】*安装——系统设置——其他高级设置——辅助功能——TTS 输出——选择安装的朗读引擎（不同品牌手机的操作方法及步骤也不同，视情况而定）。*

### 2. 如何设置屏幕方向、屏幕显示时长、显示/隐藏状态栏、显示/隐藏导航栏、音量键翻页、长按选择文本、点击总是翻下一页或自定义翻页按键？
阅读界面——“**设置**”（可上划，下面还有其他设置）。

### 3. 搜索的时候感觉手机卡顿，如何解决？
“**我的**”——“**其他设置**”——调低“**更新和搜索线程数**”。
