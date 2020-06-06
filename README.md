# Cataclysm: Dark Days Ahead 《大灾变：浩劫余生》中文本地化修改

## 注意：基于版本0.E

本存储库的文件结构及注释：
```
┣ data/
┃  ┣ title/zh_CN.title                       # 标题ASCII Art文件
┃  ┗ credits/zh_CN.credits                   # 制作人员文件
┗ lang/
   ┣ mo/zh_CN/LC_MESSAGES/cataclysm-dda.mo   # 编译后的本地化文件
   ┗ po/zh_CN.po                             # 本地化文件
```

本存储库中的内容基于 [官方Github存储库的zh_CN.po](https://github.com/CleverRaven/Cataclysm-DDA/blob/master/lang/po/zh_CN.po) （2020年5月29日 版本0.E）修改，改动如下：
- 填满了翻译。
- 修改了一部分翻译错误。
- 修改了部分标点。
- 移除了大量空格。
- 删掉和增加了少量梗。

另外，也有一些其他的修改：
- 对`\data\title\zh_CN.title`进行了修改，原始ASCII Art下面添加了本地化名称。
- 对`\data\credits\zh_CN.credits`进行了粗糙的本地化处理。
- 将引用《传送门》系列的文本修改为官方简体中文版《传送门》系列的文本（`GLaDOS文本ID：27836～27876`；`炮台ID：《传送门》27931～27975《传送门2》，27977～28059`），**注意：官方文本中炮台部分文本并非与实际译文一一对应，故部分译文保留**。为此我又玩了几次《传送门》和《传送门2》，但是并没有全部找到。
- 如有需要，请将ID为39200的翻译还原。

本项目为自用项目，但是，按照原作品所持知识共享-署名-相同方式共享 3.0（CC-BY-SA 3.0）之授权协议的要求，该项目同样以CC-BY-SA 3.0授权协议公布。