# Copyright for Typecho 自用版

这是一个 [Typecho](https://github.com/typecho/typecho) 插件，具体设置请看[原始文档说明](https://github.com/Yves-X/Copyright-for-Typecho)。

## 使用方法

直接[下载仓库](https://github.com/mikusaa/Copyright-for-Typecho/archive/master.zip)，解压后，重命名为`Copyright`。

在原插件基础上增加了一个**封面图**的字符，修改了部分文字的显示效果。

| 字段 |类型|说明|示例|
|:---:|:---:|:----|:----|
|cover|字符|封面出处|封面出处的链接|

![](https://raw.githubusercontent.com/mikusaa/Copyright-for-Typecho/dev/image.png)

不填写该字段即可关闭。

PS：如果已存在`cover`字段，下载插件后将`Plugin.php`中所有的`cover`替换成你喜欢的字段，只要不重复就行了。

